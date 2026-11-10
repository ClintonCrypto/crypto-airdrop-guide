# How to Evaluate a New Crypto Project Before You Farm It

A checklist for airdrop hunters and testnet farmers. A project can have a big points program and still be a bad use of your time — or a risk to your wallet. Run through this list before you connect a wallet, bridge funds, or grind a season.

> Rule zero: never pay to claim an airdrop, never share a seed phrase or private key, and never sign a transaction you do not understand. A real project will never ask for any of those.

## 1. Team and backers

- [ ] The team is named and public — or, if anonymous, has a track record you can verify (previous shipped products, public repos, talks).
- [ ] Backers are named with amounts and dates, not vague "top VCs". Check the announcement on the investor's own site or X account, not only on the project's page.
- [ ] The project has shipped something real: a working app, a testnet with real users, or audited code — not just a landing page and a points dashboard.

## 2. Tokenomics and the points math

- [ ] Total supply, community allocation, and unlock schedule are published in docs or a white paper — not only in a tweet.
- [ ] You can work out your rough share: how many points exist in total, how many are distributed per week, and what fraction goes to users.
- [ ] Points are not the token. A points balance has no price until a TGE date, a claim process, and a contract address exist.
- [ ] Watch for fake tokens: until the project publishes an official contract address, any token trading under its name is fake.

Worked example (verified Nov 2026): Extended's XTEN has a 1B supply with 300M (30%) for Points participants, fully unlocked at TGE — but the TGE date is still not set and the claim is not open. The conversion ended up at about 1 Xpoint ≈ 4.2857 XTEN once the Final Arc closed. Variational's VAR is the same shape: Q4 2026 window, 32% genesis airdrop, no date and no contract address yet. Points are a promise, not a payout.

## 3. Official channels only

- [ ] Find the project's X account, Discord/Telegram, docs, and app through the project's own website — never through a search result, a DM, or a reply under someone else's post.
- [ ] Bookmark the real links. Scammers clone project pages and buy ads on the real project's name.
- [ ] Claim links come only from the project's official X account or docs. Any "claim now" link in a DM, a comment, or an unfamiliar site is a scam until proven otherwise.
- [ ] The project will never DM you first about a claim, a whitelist, or "support". Support impersonation is the most common airdrop scam.

## 4. Supply-chain and download safety

- [ ] Install wallets, node software, and CLI tools only from the official release page — and check the version number against the project's announcement before you install.
- [ ] Treat every update as a new decision. A compromised release can ship through the project's own trusted channel, so an auto-update is not automatically safe.
- [ ] If a security firm or the project itself flags a version as compromised, stop: remove that version, install the clean version the project names, and rotate any keys that version could have touched. A machine that ran compromised software should be treated as fully compromised until it is wiped or rebuilt.

Real case (Nov 2026): attackers hijacked Ethersphere's own release pipeline and shipped wallet-stealing malware in the official releases of `@ethersphere/bee-js` 13.3.0 and Swarm Desktop 0.56.2. The malware stole Swarm node wallet keys and installed a persistent backdoor. SlowMist, Socket, and SafeDep all confirmed it, and GitHub's advisory said any machine that installed the package should be considered fully compromised. Clean versions: bee-js 13.2.0 and Swarm Desktop 0.56.3. The lesson is permanent: "official download" is a starting point, not a guarantee — verify the version, and keep farming keys separate from long-term holdings.

## 5. Contracts, audits, and permissions

- [ ] The contracts you interact with are verified on a block explorer and linked from the project's own docs.
- [ ] An audit exists from a firm you recognise, and you have read what it actually covered — an audit of one contract does not cover the whole app.
- [ ] Before approving a token spend, check what you are approving: amount, spender, and duration. Prefer exact amounts over unlimited approvals, and revoke approvals you no longer use.
- [ ] A brand-new, unaudited contract holding real funds is a gamble, not a farm. Testnet first, small amounts second, never your main stack.

## 6. Points program terms

- [ ] Season start and end dates, snapshot times, and epoch lengths are published — and you know which timezone they are in.
- [ ] You know how points are earned and whether they decay, expire, or reset between seasons.
- [ ] You know the claim rules in advance: self-custody wallet or exchange account, any KYC, any deadline to claim before unclaimed tokens burn.
- [ ] A program that changes its rules mid-season without notice is a yellow flag. Screenshot the terms when you join.

Standing examples (verified Nov 2026): Incentiv Epoch 0 ends 30 Nov 2026 10:00 UTC. Pacifica snapshots points every Thursday at 00:00 UTC. Ondo Perps' 50% fee discount ends 13 Nov 2026 14:00 UTC. Dates move — re-check the project's own channels before any deadline you care about.

## 7. Red flags — walk away if you see these

- A claim page that asks you to pay, connect, and sign before showing any eligibility details.
- Guaranteed returns, "risk-free" yields, or a countdown timer pressuring you to deposit now.
- A team that deletes criticism, bans questions in Discord, or only communicates through anonymous influencer posts.
- Tokenomics that change silently, or a supply figure that differs between the docs, the white paper, and the X account.
- A points program with no end date, no TGE window, and no tokenomics after months of farming — your time is the product.

## Pre-farm checklist (copy this)

1. Real team + named backers, verified on the backers' own channels.
2. Tokenomics published; I can estimate my share.
3. Official links bookmarked; claim will only come from them.
4. Contracts verified + audited; approvals kept minimal.
5. Farming wallet is separate from my main holdings.
6. Season end, snapshot, and claim rules written down with dates.
7. No payment, no seed phrase, no blind signing — ever.

If a project fails more than two checks, skip it. There is always another season. Your wallet and your time are the only capital you cannot get back.

---

*Part of the [crypto-airdrop-guide](https://github.com/ClintonCrypto/crypto-airdrop-guide) by Clinton | Crypto Professor — daily airdrops, testnets & Web3 alpha. Companion reads: [Testnet Safety Checklist](testnet-safety-checklist.md) · [Wallet Safety for Airdrop Hunters](wallet-safety-for-airdrop-hunters.md)*
