# KYC and Wallet Activation Explainer

Five recurring points of confusion, answered in plain language. Every claim is sourced or marked unconfirmed.

## 1. When KYC is required

**KYC is required for native RBNT and mainnet activity. It is not required to hold or trade wrapped RBNT on other chains.**

Redbelly Network gates access to its own Layer 1, mainnet transactions, staking, governance, behind identity verification through the Redbelly Access portal, and the onboarding documentation scopes this specifically to Redbelly's own chain. Wrapped RBNT already exists on multiple external chains: Ethereum (ERC-20) and Solana (SPL, bridged via Router Protocol's Nitro), both confirmed through Redbelly Network's own official channels. Any token living outside Redbelly's own chain sits outside that stated scope by definition, so buying, holding, or swapping it on an external DEX needs no Redbelly-side verification. The token standard on any chain beyond these two confirmed deployments has not been checked here and should not be assumed.

*Source: Redbelly Individual Onboarding SDK overview, docs.redbelly.network, for the mainnet-only scope of the identity layer. Ethereum wRBNT (ERC-20) and Solana wRBNT (SPL) confirmed via Redbelly Network's official X account (x.com/RedbellyNetwork). No chains beyond these two were checked.*

## 2. The ten-wallet-per-identity limit

**One verified identity can activate up to 10 wallets. Beyond that limit, additional wallets cannot be linked to the same KYC record.**

The limit applies per person, not per wallet, so completing KYC once covers up to 10 separate wallet addresses under that identity. A wallet requesting activation beyond the tenth is not accepted against an already-maxed identity.

*Source: reported by the contributor, who registered 10 wallets under one identity, with corroboration from two Redbelly moderators, Appie and Daniel Bressoud, in the Discord support channel.* **[COMMUNITY-REPORTED, UNCONFIRMED, NO PUBLISHED SOURCE]**

Evidence: [screenshot, Appie](https://raw.githubusercontent.com/0xDarkSeidBull/daotask18/main/public/evidence/discord-wallet-limit-appie.png) · [Discord message](https://discord.com/channels/969088176322908160/969088176515854343/1318698971429998594) &nbsp;&nbsp;|&nbsp;&nbsp; [screenshot, Daniel Bressoud](https://raw.githubusercontent.com/0xDarkSeidBull/daotask18/main/public/evidence/discord-wallet-limit-daniel.png) · [Discord message](https://discord.com/channels/969088176322908160/969088176515854343/1384913117632401469)

## 3. Typical approval wait time

**Community members report that KYC approval typically takes about 3 to 5 minutes.**

This estimate reflects turnaround reported by community members for a standard individual submission through the Redbelly Access portal, not a figure published by Redbelly itself. Submissions that need manual review, such as flagged documents or edge-case jurisdictions, can take longer than this range.

*Source: reported by the contributor, with corroboration from two Redbelly moderators, Daniel Bressoud and Appie, in the Discord support channel.* **[COMMUNITY-REPORTED, UNCONFIRMED, NO PUBLISHED SOURCE]**

Evidence: [screenshot, Daniel Bressoud](https://raw.githubusercontent.com/0xDarkSeidBull/daotask18/main/public/evidence/discord-approval-time-daniel.png) · [Discord message](https://discord.com/channels/969088176322908160/969088176515854343/1251896050780868630) &nbsp;&nbsp;|&nbsp;&nbsp; [screenshot, Appie](https://raw.githubusercontent.com/0xDarkSeidBull/daotask18/main/public/evidence/discord-approval-time-appie.png) · [Discord message](https://discord.com/channels/969088176322908160/969088176515854343/1438389387829317755)

## 4. Regional restrictions

**Eighteen jurisdictions are currently restricted from accessing the Redbelly Network platform. This list has not been confirmed as reduced from a prior version.**

Redbelly's own Terms and Conditions state the platform is not offered to residents or tax residents of: Afghanistan, Central African Republic, North Korea, Democratic Republic of the Congo, Guinea-Bissau, Iran, Iraq, Lebanon, Libya, Myanmar, Russia, Somalia, South Sudan, Sudan, Syria, Ukraine, Yemen, and Zimbabwe. Residents or tax residents of any jurisdiction on this list cannot proceed with KYC or mainnet access, regardless of wallet or exchange used. The Terms name only these excluded jurisdictions; they do not separately state that residency outside this list guarantees KYC approval.

*Source: Redbelly Network Terms and Conditions, Clause 15, redbelly.network/terms-and-conditions. Note: this document reflects currently restricted jurisdictions. No official record of a prior, larger restricted list was found, so the claim that restrictions have been reduced is not confirmed and is not repeated here as fact.*

## 5. KYC as a prerequisite for staking

**Staking RBNT requires completed KYC, because staking is a write action on Redbelly's own chain, gated by the same access-credential requirement as any other mainnet transaction.**

Redbelly's developer portal states that before a user is granted access to the network, they must claim an access credential, proved with a photo identity document and biometric checks, before they can self-enable write access to the network through a specific network smart contract. Staking works by calling the deposit function on Redbelly's staking contract, which is exactly this kind of write action, so it falls under the same access-credential requirement. The whitepaper separately confirms staking as a core RBNT utility on Redbelly's own chain, not a wrapped external token.

*Source: Redbelly Network developer portal, User access and Staking pages, vine.redbelly.network/identity/user-access and vine.redbelly.network/nodes/staking; and Redbelly Network whitepaper, redbelly.network/whitepaper.*

---

Two claims above (ten-wallet limit, approval wait time) are reported firsthand by the contributor, with corroboration from two Redbelly moderators in Discord, but no published official document. Screenshots and direct message links for both moderators are included with each claim. They are marked community-reported and unconfirmed per task requirements. All other claims are cited to an official Redbelly source.
