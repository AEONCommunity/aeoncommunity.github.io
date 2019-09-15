Aeon Timeline
-------------

## 2014

#### June

  - [6] Aeon was launched 6_6_2014 UTC with no premine, no instamine, and no dev-fund with a hard fork of Monero code

#### July

#### August

#### September

  - [11] v0.8.8.3 Emergency release to fix the block 202612 attack
  
  - [15] v0.8.8.4 Point release: testnet, FreeBSD

#### October

#### November

#### December

  - [2] v0.8.8.5 Point release: OpenAlias support, per-kb fees, multi-lang mnemonics, MSVC -> msys2 on Windows, DNS / file checkpointing
  
  - [8] v0.8.8.6 Point release: fixes broken Windows static builds, multilang mnemonic bug fixes

## 2015

#### January

#### Feburary 

#### March

#### April

#### May

#### June

#### July

  - [21] v0.9.0.0 Phoenix Release: Hard fork block 592000 changing PoW to Cryptnight-Lite and block target to 4 minutes, Enforce checkpoints on stored blockchain file (from Monero), Triangular distribution on mixin selection (from Monero), Mixin ring fix (from Boolberry), Updated seed node, Tree-hash fix (from Monero), Updated checkpoint table

#### August

  - [17] v0.9.1.1 Point release: Fix diff command showing incorrect hash rate after hard fork 1, Small improvement to performance of daemon miner (1-2%), Added backup seed node, Lower mining priority for anon-impairing (<2 mixins) tx
Various portability fixes (mostly from Monero), Small reduction to memory usage (tens of MB), Add IP blocking for misbehaving nodes (adapted from Boolberry), Update checkpoint table

#### September

  - [3] v0.9.4.0 Point release: Revert memory reduction, Revert stuck tx removal, Optimize sync within checkpoint zone, Update seed node list

#### October

  - [9] v0.9.5.0 Point release: SECURITY: Fix upnp buffer overflow, Fix compile error with gcc 5.1.0, Fix node unblocking message formatting, Code clean ups

#### November

  - [5] v0.9.6.0 Point release: Fix mixin output selection to match wallet output selection, Slightly reduce wallet maximum tx size; should speed up confirmation rate especially for split transactions

#### December

## 2016

#### January

#### Feburary 

#### March

#### April
  
#### May

#### June

#### July

#### August

#### September

#### October

#### November

#### December

## 2017

#### January

#### Feburary 

  - [23] v0.9.7.1 Point Release: Includes preliminary code for support for ringct (not yet functional or enabled), Include upstream fixes, Performance improvement on non-Intel platforms

#### March

  - [4] v0.9.8.4 Point release: Hard fork at block height 798358, this release corrects a problem which allowed a recent block to enter the chain data store despite a missing transaction. Also contains additional bug fixes from Monero (credit moneromooo and warptangent), All nodes will require resyncing after installing this update. In addition any blocks that are part of the invalid chain starting at height 798358 will be rejected. Nodes continuing to advertise the invalid blocks will be dropped and eventually banned. This may initially produce a high volume of error messages.

  - [29] v0.9.9.0 Point release: Includes reliability and stability fixes, Updates embedded miniupupc with latest upstream fixes, Resolves build issues with newer compiler/platform versions (some from Monero upstream)

#### April

  - [4] v0.9.10.0 Point release: This minor release addresses some possible causes for poor performance and lockups seen in 0.9.9.0. In addition it fixes a build problem on some versions of Mac OS X. Fix for possible deadlock, Reduce unnecessary lock holding, Mac build fix from upstream (@radfish from monero)

  - [5] v0.9.11.0 Point release: Release resolves a deadlock issue introduced in 0.9.9.0 which caused the daemon to occasionally hang. 
  
  - [23] v0.9.12.0 Point release: A future update (not yet scheduled) will begin enforcing the minimum relay fee equal to the current default fee, so nodes that have not yet updated to a minimum of 0.9.12.0 will then be disconnected and banned. Fixes some Windows build issues, Add option to disable blockchain auto-save (useful to reduce swapping on low-memory nodes) ,Prioritize transactions by fee/byte, Disable relay of transactions with legacy fee lower than current default

#### May

#### June

#### July

#### August

#### September

  - [30] v0.9.13.0 Point release: Update for RPC users. Anyone operating an important node or mining (solo mining or operating a pool; not relevant to pool client miners) should review the new deployment notes. Numerous portability and compilation fixes (stoffu, appveyor), RPC wallet exception handling for improved reliability (upstream from XMR/QCN, sammy007), Added deployment notes in README 

#### October

  - [27] v0.9.14.0 Point release: This was the last release for the Legacy Aeon software. This optional enhancement release adds one new feature and one feature from upstream (Monero). The release is fully compatible and contains no significant bug fixes. As such the previous daemon and/or wallet can be used interchangeably with this one if the new features are not needed.
The --restricted-rpc daemon option (ported from Monero by LesPristy) disables some unsafe RPC requests for use with public nodes. The --fee-multiplier simplewallet option increases all fees by a factor of 1 (default; unchanged) to 100 (recommended: 2 or 3). This can assist in getting urgent transactions confirmed when there is a tx pool backlog. May also be used when creating mixin 0 transactions to bid for the one available tx slot per block (a 0 mixin with a fee multiplier of 2 may still be less expensive and/or confirm faster than a mixin 2 with a fee multiplier of 1, depending on the details of the transaction and network conditions). Additional changes were: README cleanup (xmr-eric), Fix for incorrect hash rate displayed by daemon diff command, Added instructions for manual cmake to README

#### November

#### December

## 2018

#### January

#### Feburary 

#### March

#### April

#### May

  - [24] Aeon Sophia Released. See all release notes [Here](https://github.com/aeonix/aeon/releases/tag/v0.12.0.0)

#### June

  - [3] v0.12.0.0 Hard Fork height 963500. Aeon Rebased to Monero's latest codebase with RingCT disabled, CryptoNight-Lite variant 1, limited use of ringsize 1, ban ringsize 2. Aeon also Integrated a remake of Monero's GUI wallet with the help of (DSC) from the Monero team. 
  
  - [14] v0.12.1.0 Point release: Merge pull request #31 from stoffu/aeon-wdouble, wallet2: fix double counting outs if the tx pubkey is duplicated /monero#3985
  
  - [16] v0.12.1.1 Point release: This recommended point release fixes three wallet bugs which can result in failed transactions or missed payments under certain conditions. It also includes improved installation instructions for Ubuntu/Debian. Note: 0.12.1.1 replaces the withdrawn 0.12.1.0, which was missing an updated version string. There are no other changes. Merge pull request #32 from stoffu/aeon-bump-0.12.1.0, bump version for 0.12.1 point release
  
  - [20] v0.12.2.0 Merge pull request #37 from stoffu/aeon-fill-template-fix, tx_pool.fill_block_template: fix miscalculation of total size and fee
  
  - [20] v0.12.2.1 Point Release: This point release fixes a bug in block construction resulting in lower block rewards under some conditions involving very large transactions. Recommended update for nodes running a mining pool and users who are solo mining, otherwise updating is not needed. Note: replaces withdrawn 0.12.2.0, which did not update the version string Merge pull request #38 from stoffu/aeon-bump-0.12.2, bump version to 0.12.2
  
  - [26] v0.12.3.0 Point release: This recommended update improves wallet handling of split transfers, resulting in smaller transactions and lower fees. Merge pull request #40 from stoffu/aeon-bump-0.12.3, bump version to 0.12.3

#### July

  - [7] v0.12.4.0 Point release: SOURCE CODE ONLY. This recommended point release further optimizes transaction size and fees by ignoring inefficient tiny dust outputs. This feature can be controlled using the ignore-fractional-outputs option (default on). Merge pull request #42 from stoffu/aeon-bump-0.12.4, bump version to 0.12.4
  
  - [9] v0.12.5.0 Point release: Contains additional upstream fix to ensure outputs are processed only once. Merge pull request #45 from stoffu/process-outs-once, wallet2: ensure outputs are processed only once /monero#4118

#### August

#### September

  - [27] v0.12.6.0 Point release: Dozens of upstream performance, reliability and security patches. Improved packaging for (unfinished/non-usable) Ledger wallet support, Several documentation improvements from the AEON community, Disable incorrect/obsolete DNS lookups. Fixed P2P network issue that prevent DoS attacks against the nodes. *All users receiving payments should update ASAP to protect against the cryptonote duplicate output coin burning attack described in https://getmonero.org/2018/09/25/a-post-mortum-of-the-burning-bug.html (if unable to update immediately, suspend receiving payments until updated).*  Merge pull request #54 from stoffu/aeon-bump-0.12.6, bump version to 0.12.6

#### October

#### November

  - [27] v0.12.7.0 Point release: SOURCE CODE ONLY. Dozens of upstream performance, reliability and security patches
Several documentation and configuration improvements from the AEON community. Daeomon update to help prevent possible database corruption and loss of synchronization with the rest of the network for P2P users. Merge pull request #78 from stoffu/aeon-bump-0.12.7, bump version to 0.12.7
  
  - [30] v0.12.8.0 Point release: This maintenance release fixes a problem that existed in 0.12.7.0 only when using the wallet on Windows, and in addition contains a cosmetic improvement to logging and some documentation cleanup. If you are not running Windows there is no need to update from 0.12.7.0. Note: The initial linux binary was built with an incorrect version tag. This has now been corrected. Merge pull request #78 from stoffu/aeon-bump-0.12.7, bump version to 0.12.7

#### December

  - [4] First Community meeting held on the Discord channel [HERE](https://github.com/AEONCommunity/CommunityMeetUps-logs/blob/master/12_4_2018%20Discord%20log.md)

## 2019

#### January

  - [8] Aeon added to Bisq's official release: https://github.com/bisq-network/bisq/releases/tag/v0.9.2

  - [17] Community created [Tester Central repository](https://github.com/AEONCommunity/TesterCentral) for aiding in testing anything Aeon related. 
  
#### Feburary

  - [1] First ever [Aeon Community Giveaway](https://twitter.com/AeonCommunity/status/1091515045073297409). Ledger NanoS was gifted to an Aeon community member!
  
  - [4] Community CLI and GUI beta testing guidelines added to [community repo](https://github.com/AEONCommunity/TesterCentral) 
  
  - [4] Aeon RPC documentation guides started [here](https://github.com/AEONCommunity/RPC-Usage/blob/master/RPC%20Commands.md)

  - [28] Community Meeting [Logs](https://github.com/AEONCommunity/CommunityMeetUps-logs/blob/master/2_28_2019%20Meeting%20Logs.md)
  
#### March

  - [1] Followup Community Meeting [Logs](https://github.com/AEONCommunity/CommunityMeetUps-logs/blob/master/3_1_2019%20Meeting%20Logs.md)
  
  - [1] K12 Proof of Work [proposal](https://old.reddit.com/r/Aeon/comments/aw2xhn/proposal_to_switch_to_sha3_proof_of_work/) submitted to community by Stoffu
  
  - [9] Aeon WooCommerce Gateway integration added to [community repo](https://github.com/AEONCommunity/aeon-woocommerce-gateway)
  
  - [9] v0.12.9.0 Point release: Several dozen upstream reliability, security, and performance improvements (cli), Fixes for upstream vulnerabilities not believed exploitable in AEON but patched for defensive and maintenance purposes (cli), Various build and packaging improvements from the AEON community.
  
  - [13] Aeon Onion Block Expolorer repository added to [community repository](https://github.com/AEONCommunity/onion-aeon-blockchain-explorer) and 3 new block explorers put into operation. 
  
  - [19] Spanish Translations added to community translation repository for Aeon Main website along with core cli/gui readme's. 
  
  - [28] Polish Translations added to community translation repository for Aeon Main website along with core cli/gui readme's.
  
  - [28] Aeon Shell-Map added to [community repository](https://github.com/AEONCommunity/aeon-shell-map) giving users the ability to view global nodes on a graphical scale.
  
#### April

  - [3] Aeon added to [DeltaDirect App](https://delta.app/en/crypto/aeon/aeon)

  - [10] Esperanto Translation added to community translation repository for Aeon main website.
  
  - [11] German Translations added to community translation repository for Aeon Main website along with core cli/gui readme's.

#### May

  - [21] StelthEX adds Aeon to their [exchange platform](https://stealthex.io).
  
  - [31] Aeon community brings [Thunderosa onboard](https://old.reddit.com/r/Aeon/comments/bv8mo1/aeon_marketing_update/) as a seasoned marketing member of the Monero community.

#### June

  - [6] Aeon's 5th Birthday! 
  
  - [21] Russian translations added for Aeon.cash and core coding documentation.
  
  - [27] Aeon added to [slips list](https://github.com/satoshilabs/slips/pull/672) for future hardware support of devices like ledger or trezor. 

#### July

  - [5] Initial new marketing [documents](https://old.reddit.com/r/Aeon/comments/c9bk1b/aeon_marketing_initial_document/) released by Thunderosa. 

  - [13] Aeon notes as [coin of the day](https://old.reddit.com/r/Aeon/comments/cckyox/aeon_currently_coin_of_the_day/) on Lunar Crush. 
  
  - [19] Aeon added to the [Matrix Chat](https://matrix.to/#/#aeon:matrix.org) platform. 

  - [29] Aeon's website was re-designed to allow multi-language support and refresh its appearance for a more modern look.

#### August

  - [14] New [block explorer](https://github.com/aeonix/aeonix.github.io/pull/70) added to our website.

  - [15] Cleanup of website format and minor styling changes.
  
  - [15] [AeonLW](https://github.com/BigslimVdub/AeonLW) released to public, an Electron wallet for Aeon.
  
  - [26] [Russian and Chinese](https://github.com/aeonix/aeonix.github.io/pull/82) translations added to our website. 
  
  - [27] SwapSpace integrates Aeon to their servicing platform.
  
  - [30] Preliminary binaries released for v0.13.0 fork by Stoffu.
  
#### September

  - [1] HitBTC re-opens support for Aeon deposits and withdrawals.

  - [2] [French](https://github.com/aeonix/aeonix.github.io/pull/84) translations added to our website. 
