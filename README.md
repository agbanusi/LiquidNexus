## NexusLend: Bridging Liquidity, Empowering Credit

<br>

## Description

NexusLend is a forward-thinking, multi-chain lending protocol that disrupts traditional liquidity models. It lets you borrow against your staked assets without having to worry about collateral or bridging hassles. The protocol aggregates assets from across chains to unlock flexible, collateral-free borrowing—up to 70% of your total staked value, or even 90% if your credit score is in the top tier. NexusLend provides an intuitive interface for both casual users and degens looking for higher yields.

## Overview

NexusLend redefines liquidity by aggregating staked assets across chains. It enables users to access liquidity without the need for traditional collateral—leveraging a dynamic credit scoring system and a mobile-focused UX to deliver a seamless, cross-chain lending experience.

## Key Features

- Collateral-Free Borrowing: Borrow up to 70% of your total staked asset value across chains, or up to 90% for users with superior credit scores.

- Cross-Chain Liquidity Access: Deposit your liquidity tokens once and gain access to lending on any supported chain—no manual bridging required.

- Liquidity Staking & Impermanent Loss Mitigation: Stake your liquidity tokens and earn interest that not only compensates for impermanent loss but also boosts your overall yield.
- Credit Scoring System: A transparent mechanism that rewards active, reliable users with enhanced borrowing limits.

- Semi-Fixed Interest Rates: Enjoy predictable, stable borrowing costs within a fixed variation band.

## How It Works

- Deposit & Stake: Users deposit liquidity tokens on any supported chain. These tokens are staked and aggregated to determine your total lending capacity.

- Credit Evaluation: The protocol calculates a credit score based on your staking history and participation, unlocking higher borrowing limits for users scoring above 80%.

- Borrowing Process: With your staked assets as backing, you can borrow funds—up to 70% (or 90% with a high credit score) of your total aggregated value—without the need for additional collateral.

- Interest & Rewards: Earn interest on your staked assets to offset impermanent loss while taking advantage of competitive APYs.

- Cross-Chain Access: Leverage a unique liquidity switcher that allows you to borrow on any chain without physically moving your assets.

## Roadmap & Future Directions

- Enhanced Credit Algorithms: Further refine the credit scoring mechanism to more accurately reward reliable participation.

- Broader Cross-Chain Integration: Expand support for additional blockchains, ensuring seamless liquidity access regardless of the chain.

<br>
<br>

# Building and Testing

- First copy `.env.example` to `.env` and fill in archival node URLs as well as a mnemonic (hardhat only)
- To download needed modules run `npm install`
- This repository contains scripts to compile using both Hardhat and Foundry
- You will need to [install foundry](https://book.getfoundry.sh/getting-started/installation)
- Install foundry submodules `git submodule init && git submodule update`

Compilation

- `forge build`
- `npx hardhat compile`

<br>
<br>

# License

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
