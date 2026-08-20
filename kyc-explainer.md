# KYC and Wallet Activation Explainer

Five recurring points of confusion, answered in plain language. Every claim is sourced or marked unconfirmed.

## 1. When KYC is required

**KYC is required for native RBNT and mainnet activity. It is not required to hold or trade wrapped RBNT on other chains.**

Redbelly Network gates access to its own Layer 1 (mainnet transactions, staking, governance) behind identity verification through the Redbelly Access portal. Wrapped RBNT on Ethereum is a standard ERC-20 token with no Redbelly-side identity check, so buying, holding, or swapping it there does not require Redbelly KYC. The same principle should extend to wrapped RBNT on other chains, since any token living outside Redbelly's own chain sits outside its identity layer by definition, but the exact token standard on each additional chain (ERC-20, SPL, or otherwise) has not been individually verified here and should not be assumed uniform.

*Source: Redbelly Individual Onboarding SDK overview, docs.redbelly.network. Wrapped-token distinction inferred from Ethereum wRBNT operating as a standard ERC-20 outside Redbelly's identity layer; the same outside-the-identity-layer logic is assumed, not separately verified, for wrapped RBNT on other chains.*

## 2. The ten-wallet-per-identity limit

**One verified identity can activate up to 10 wallets. Beyond that limit, additional wallets cannot be linked to the same KYC record.**

The limit applies per person, not per wallet, so completing KYC once covers up to 10 separate wallet addresses under that identity. A wallet requesting activation beyond the tenth is not accepted against an already-maxed identity.

*Source: reported by the contributor, who states they registered 10 wallets under one identity, with informal corroboration from a Redbelly moderator in the Discord support channel. No screenshot or message link is attached to verify this.* **[COMMUNITY-REPORTED, UNCONFIRMED, NO PUBLISHED SOURCE]**

## 3. Typical approval wait time

**Most KYC submissions are approved in about 3 to 5 minutes.**

This is the typical turnaround reported for a standard individual submission through the Redbelly Access portal. Submissions that need manual review, such as flagged documents or edge-case jurisdictions, can take longer than this range.

*Source: reported by the contributor, with informal corroboration from a Redbelly moderator in the Discord support channel. No screenshot or message link is attached to verify this.* **[COMMUNITY-REPORTED, UNCONFIRMED, NO PUBLISHED SOURCE]**

## 4. Regional restrictions

**Eighteen jurisdictions are currently restricted from accessing the Redbelly Network platform. This list has not been confirmed as reduced from a prior version.**

Redbelly's own Terms and Conditions state the platform is not offered to residents or tax residents of: Afghanistan, Central African Republic, North Korea, Democratic Republic of the Congo, Guinea-Bissau, Iran, Iraq, Lebanon, Libya, Myanmar, Russia, Somalia, South Sudan, Sudan, Syria, Ukraine, Yemen, and Zimbabwe. Residents or tax residents of any jurisdiction on this list cannot proceed with KYC or mainnet access, regardless of wallet or exchange used. The Terms name only these excluded jurisdictions; they do not separately state that residency outside this list guarantees KYC approval.

*Source: Redbelly Network Terms and Conditions, Clause 15, redbelly.network/terms-and-conditions. Note: this document reflects currently restricted jurisdictions. No official record of a prior, larger restricted list was found, so the claim that restrictions have been reduced is not confirmed and is not repeated here as fact.*

## 5. KYC as a prerequisite for staking

**Staking RBNT requires completed KYC, because staking is a write action on Redbelly's own chain, gated by the same access-credential requirement as any other mainnet transaction.**

Redbelly's developer portal states that before a user is granted access to the network, they must claim an access credential, proved with a photo identity document and biometric checks, before they can self-enable write access to the network through a specific network smart contract. Staking works by calling the deposit function on Redbelly's staking contract, which is exactly this kind of write action, so it falls under the same access-credential requirement. The whitepaper separately confirms staking as a core RBNT utility on Redbelly's own chain, not a wrapped external token.

*Source: Redbelly Network developer portal, User access and Staking pages, vine.redbelly.network/identity/user-access and vine.redbelly.network/nodes/staking; and Redbelly Network whitepaper, redbelly.network/whitepaper.*

---

Two claims above (ten-wallet limit, approval wait time) are reported firsthand by the contributor, with informal corroboration from a Redbelly moderator in Discord, but no published official document and no screenshot or message link on file. They are marked community-reported and unconfirmed per task requirements. All other claims are cited to an official Redbelly source.
