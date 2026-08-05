# FLEC Hub — Flare Summer Signal 2026

## 1. What Is FLEC Hub?

FLEC Hub is a Spanish-first bilingual education-to-action platform built for Spanish-speaking users worldwide. It guides participants from understanding Flare to preparing a wallet, using test assets in a real application flow, verifying blockchain activity, and progressing through an optional educational experience on Flare Testnet Coston2.

The working model turns concepts into practice. Participants learn about Flare, FAssets, FXRP, and FTSO; connect MetaMask or Bifrost Wallet; acquire test assets; use test FXRP in the OVO Genesis experience; verify what happened on-chain; and continue into OVO-to-Nest progression, Proof of Participation (POP), Registry, and Ranking experiences.

FLEC Hub grew from LATAM and Colombian community work, but its product audience is broader: Spanish-speaking users worldwide who benefit from localized education, guided wallet preparation, and a clear path from learning to verifiable action.

## 2. The Problem We Solve

Web3 education often stops before the moment a learner must use a wallet, approve an asset, understand a transaction, or verify the result. That gap can be larger for Spanish-speaking and mobile-first users when technical material, wallet interfaces, and ecosystem onboarding are fragmented across different resources.

FLEC Hub closes that gap in one guided journey. Education comes first, knowledge checks reinforce understanding, wallet-safety guidance prepares the participant, and Coston2 provides a low-risk environment for practical activity. For ecosystem partners, the same model creates a reusable onboarding and activation layer rather than a one-time tutorial.

## 3. How the Working Model Operates

The model follows a simple progression:

1. **Education:** bilingual lessons introduce Flare, FAssets, FXRP, and FTSO.
2. **Wallet preparation:** safety guidance and knowledge checks come before blockchain actions.
3. **Test-asset acquisition:** participants connect a supported wallet, confirm Coston2, and access the official Coston2 faucet.
4. **Practical utility:** test assets become inputs to guided product experiences rather than remaining abstract examples.
5. **Verification:** transaction receipts, contract events, ownership, and progression state show what happened on-chain.
6. **Progression:** participants can continue through optional OVO, Nest, POP, Registry, and Ranking experiences.

This structure lets FLEC Hub teach first and activate second while keeping blockchain actions voluntary.

## 4. What We Built

The deployed hackathon MVP combines:

- synchronized Spanish and English education with review and retry;
- wallet-safety preparation and bilingual knowledge checks;
- a guided FLEC character and browser voice tutor;
- MetaMask integration plus WalletConnect support for Bifrost Wallet;
- Coston2 network and official faucet guidance;
- a controlled TFLEC educational reward using EIP-712 authorization;
- test-FXRP utility in the OVO Genesis NFT experience;
- OVO-to-Nest progression with on-chain state restoration;
- POP restoration, OVO Registry, verified-participant Ranking, and persistent learning progress.

The browser experience coordinates education and wallet interaction, while Coston2 contracts provide verifiable asset, ownership, and progression state. The public documentation intentionally focuses on the product and verifiable integration without exposing credentials, secrets, or private operational data.

## 5. Participant Journey

A participant can choose Spanish or English, complete the Flare/FAssets/FXRP/FTSO learning path, review wallet-safety guidance, and connect MetaMask or Bifrost Wallet. The Hub then guides the participant to confirm Flare Testnet Coston2 and access the official Coston2 faucet, where test FXRP can be obtained and held in the participant's wallet.

Inside the guided application flow, the participant authorizes use of test FXRP and uses it to mint an OVO Genesis NFT. The experience verifies the transaction receipt, relevant contract event, token ID, wallet association, and NFT ownership on-chain. The participant can then continue to OVO-to-Nest progression, restore progression state from the blockchain, and complete the POP, Registry, and Ranking portions of the journey.

FLEC Hub helps participants understand that an FAsset is not only a theoretical concept. Through the guided Coston2 experience, test FXRP can be obtained, held in a wallet, authorized, used inside an application, and verified on the Flare blockchain.

## 6. Bounty 1 — Interoperable Asset Products

FLEC Hub contributes an education, onboarding, and activation layer for interoperable assets. Instead of separating learning from product use, the MVP connects the two in a single path:

**Education → wallet preparation → test-asset acquisition → interoperable asset utility → smart-contract interaction → blockchain verification → user progression**

This strengthens the adoption path around FAssets: a participant learns what FXRP represents, obtains the test asset, holds it in a wallet, uses it in an application, and verifies the resulting NFT activity on Flare. For protocols and ecosystem teams, FLEC Hub provides a model for turning localized education into better-prepared users who have already practiced a verifiable asset interaction.

## 7. Technical Flare Integration

The MVP runs on Flare Testnet Coston2, Chain ID 114. MetaMask and Bifrost Wallet are supported through the product's wallet flows, with WalletConnect used for Bifrost. The application coordinates test-asset guidance with Coston2 smart contracts for rewards, OVO minting, and OVO-to-Nest progression.

The controlled TFLEC reward path uses EIP-712 authorization so claim parameters can be signed off-chain and validated by the reward contract. On-chain verification uses transaction receipts and contract events rather than UI state alone. For the OVO path, the Hub can associate the transaction with its token ID and connected wallet, confirm ownership through `ownerOf`, and restore progression state when a participant returns. Registry, Ranking, and POP restoration extend that verified state into the participant experience.

This is intentionally enough technical evidence to make the GitHub record auditable without turning the hackathon narrative into a full architecture report.

## 8. Testing and Community Validation

Validation evidence includes:

- verified OVO demo journeys;
- confirmed TFLEC reward claims;
- confirmed test-FXRP OVO minting;
- confirmed OVO ownership and OVO-to-Nest progression;
- confirmed POP restoration, Registry, and Ranking behavior;
- Spanish and English journey validation;
- MetaMask desktop and mobile testing;
- Bifrost Wallet testing;
- **25/25 focused final technical tests passed**;
- community validation during the FlareColombia event in Pereira, Colombia.

The official [hackathon demo video](https://www.youtube.com/watch?v=zrfzX0v-cAo) combines a product walkthrough with live community validation in Colombia, showing the product in both technical and community contexts.

## 9. How FLEC Hub Helps Flare

FLEC Hub expands Flare onboarding through a Spanish-first product designed for Spanish-speaking users worldwide. It makes ecosystem concepts actionable, gives FAssets and FXRP a practical learning context, reinforces wallet safety before transactions, and lets participants verify results instead of trusting a completion screen.

For Flare protocols, wallets, infrastructure teams, educators, and community organizations, the Hub can become a reusable activation surface for localized campaigns. Its Colombian and LATAM roots provide real community feedback, while the platform design can serve Spanish-speaking communities globally.

## 10. Future Economy and Business Model

FLEC Hub is designed as a **B2B2C education and activation platform**. Potential customers and partners include Flare protocols, wallets, infrastructure providers, sponsors, universities, educational organizations, Web3 communities, content creators, and training programs.

Potential revenue streams include sponsored educational modules, protocol onboarding, Spanish localization, audiovisual production, wallet onboarding services, tutorials, workshops, ecosystem campaigns, recurring partnerships, and privacy-conscious aggregate reporting. Participant rewards are separate from FLEC Hub operating revenue and are defined independently by each campaign.

The official FLEC token already exists on Flare Mainnet:

`0xb71E9a49a3151484753eacF9513b6876C6BEa62b`

Partners may acquire and use FLEC for educational modules, localization, tutorials, audiovisual production, onboarding campaigns, community activations, and future Hub services. FLR may complement specific campaign budgets or participant incentives, while FLEC remains the intended primary service utility within this model.

The intended flywheel is:

**Partners acquire FLEC → Pay for education and onboarding → FLEC Hub produces guided experiences → Users learn, complete modules, and may receive campaign-defined rewards → Partners receive better-prepared users → Resources fund new modules and campaigns → FLEC gains utility and recirculation.**

Campaign rewards are defined separately per campaign. No participant receives an automatic reward merely by using the Hub, and campaign-funded participant rewards are not treated as operating revenue.

## 11. Optional NFT Progression and Guardian Vision

The optional progression vision is:

**OVO → Nest → Feathers → Flight → Guardian**

These NFTs may serve as identity, progress, recognition, participation, personalization, and verifiable educational-history layers. They are not required for foundational education.

Guardian may become eligible for variable ecosystem benefits such as campaign benefits, sponsor-funded rewards, randomized airdrops, and separately allocated FTSO-related distributions. If a future FLEC FTSO operation allocates resources to ecosystem programs, any Guardian-related distribution would require a separate allocation and defined eligibility rules.

Guardian does not promise fixed yield, guaranteed income, automatic payments, permanent FTSO revenue rights, FTSO ownership, automatic governance, or mandatory delegation. Eligibility, funding, distribution methods, frequency, and recipient selection remain subject to technical, economic, legal, security, and governance review.

## 12. Roadmap

The next product stages can deepen the same education-to-action model: continue Coston2 validation, expand partner-ready modules, add broader interoperable-asset experiences, connect appropriate Mainnet FLEC utility, and develop the optional NFT progression and Guardian model under separate review.

The current guided Coston2 experience introduces participants to the practical acquisition and use of test FXRP. Future versions may expand this foundation into user-initiated FAssets minting and redemption, additional interoperable assets, deeper protocol integrations, and Mainnet journeys. FTSO operations and any related Guardian economy also remain future work subject to their own technical, economic, legal, security, and governance validation.

## 13. Deployments and Project Links

| Deployment | Value |
|---|---|
| Network | Flare Testnet Coston2 |
| Chain ID | 114 |
| TFLEC | `0x2e3417ABC7b94276ac536CfD7Fa508adf507E311` |
| Reward Authorization | `0xBf108BeA1f535DB1B77b7389BA86490e95fbce3c` |
| OVO Genesis | `0xa99e55116a1807b7ad06b852e55bd21b9eb36fe1` |
| OVO-to-Nest | `0x8381572B4e9EeB2fFb3a0836A0fF00237407440a` |

Project links:

- Live application: https://flareflec.xyz/hub
- DoraHacks: https://dorahacks.io/buidl/46281
- Demo video: https://www.youtube.com/watch?v=zrfzX0v-cAo
- Public documentation: https://github.com/FlareFlec/FLEC-Docs
- Community: https://linktr.ee/FLAREFLEC
- X: https://x.com/flareflec

## 14. Safety Notice

- TFLEC, test FXRP, and the current demo NFT and progression contracts operate on Flare Testnet Coston2 and have no monetary value. They are separate from the official FLEC token on Flare Mainnet.
- No parity, conversion, exchange, or redemption between TFLEC and official FLEC is promised.
- Coston2 participation creates no automatic Mainnet right, financial return, governance right, campaign reward, or future entitlement.
- Future Guardian benefits, if implemented, remain variable, separately defined and funded, and subject to further review.
- FLEC Hub does not request seed phrases or private keys.
- Blockchain actions are voluntary and should be reviewed by participants before approval.

---

**Last Updated:** August 2026
