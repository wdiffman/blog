+++
title = 'Arkham Zcash Claims'
date = 2026-01-06T10:24:58Z
draft = false
+++

Last month, blockchain surveillance company [Arkham announced that they're able to trace 53% of ZCash transactions](https://nitter.poast.org/arkham/status/1998122628390048174).
Obviously, this was a clickbait marketing spin as the community [quickly](https://nitter.poast.org/mert/status/1998290659284042123) [commented](https://nitter.poast.org/vinibarbosabr/status/1998325143966294436).

So why is this just clickbait?
ZCash supports four value pools, one transparent and three shielded pools. The transparent pool is very similar to Bitcoin's transparent nature, where anyone can see value transfers between addresses. The shielded pools (Sprout, Sapling and Orchard) offer privacy. In fact, the Orchard pool is the most advanced one of them, introduced with the most recent [Halo 2 proof system](https://zechub.wiki/zcash-tech/halo). ZCash has effectively already accomplished what Monero is trying to build with their [Full Chain Membership Proofs](https://www.getmonero.org/2024/04/27/fcmps.html) - ensuring sender privacy as transactions within the Orchard pool cannot be tied to each other.

Now of course, users also do create transactions between the transparent pool (T) and the shielded pools (Z), and partial information is observable from these transactions.
Transactions that bridge between these pools are frequently called:
- Shielding (T-Z)
- Deshielding (Z-T)

But everything that happens inside the shielded pool (Z-Z), enjoys great privacy.



