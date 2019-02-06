Aeon Timeline
-------------

### 2014

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

### 2015

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

### 2016

#### January

#### Feburary 

  - [23] v0.9.7.1 Point Release: Includes preliminary code for support for ringct (not yet functional or enabled), Include upstream fixes, Performance improvement on non-Intel platforms

#### March

  - [4] v0.9.8.4 Point release: Hard fork at block height 798358, this release corrects a problem which allowed a recent block to enter the chain data store despite a missing transaction. Also contains additional bug fixes from Monero (credit moneromooo and warptangent), All nodes will require resyncing after installing this update. In addition any blocks that are part of the invalid chain starting at height 798358 will be rejected. Nodes continuing to advertise the invalid blocks will be dropped and eventually banned. This may initially produce a high volume of error messages.

  - [29] v0.9.9.0 Point release: Includes reliability and stability fixes, Updates embedded miniupupc with latest upstream fixes, Resolves build issues with newer compiler/platform versions (some from Monero upstream)

#### April

  - [4] v0.9.10.0 Point release: This minor release addresses some possible causes for poor performance and lockups seen in 0.9.9.0. In addition it fixes a build problem on some versions of Mac OS X. Fix for possible deadlock, Reduce unnecessary lock holding, Mac build fix from upstream (@radfish from monero)

  - [5] v0.9.11.0 Point release: Release resolves a deadlock issue introduced in 0.9.9.0 which caused the daemon to occasionally hang. 
  
#### May

#### June

#### July

#### August

#### September

#### October

#### November

#### December

### 2017

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

### 2018

#### January

#### Feburary 

#### March

#### April

#### May

  - [24] v0.12.0.0 Point Release: Merge pull request #13 from stoffu/aeon-v0.12.0-checkpoints, update checkpoints

#### June

  - [3] v0.12.0.0 Sophia Rebase Release: Aeon hardfork block height 963500 to add LMDB and catch up to Monero v0.12.0.0 code. 
  - [14] v0.12.1.0 Merge pull request #31 from stoffu/aeon-wdouble, wallet2: fix double counting outs if the tx pubkey is duplicated /monero#3985
  - [16] v0.12.1.1 Merge pull request #32 from stoffu/aeon-bump-0.12.1.0, bump version for 0.12.1 point release
  - [20] v0.12.2.0 Merge pull request #37 from stoffu/aeon-fill-template-fix, tx_pool.fill_block_template: fix miscalculation of total size and fee
  - [20] v0.12.2.1 Merge pull request #38 from stoffu/aeon-bump-0.12.2, bump version to 0.12.2
  - [26] v0.12.3.0 Merge pull request #40 from stoffu/aeon-bump-0.12.3, bump version to 0.12.3

#### July

  - [7] v0.12.4.0-aeon Merge pull request #42 from stoffu/aeon-bump-0.12.4, bump version to 0.12.4
  - [9] v0.12.5.0-aeon Merge pull request #45 from stoffu/process-outs-once, wallet2: ensure outputs are processed only once /monero#4118


#### August

#### September

  - [27] v0.12.6.0-aeon Merge pull request #54 from stoffu/aeon-bump-0.12.6, bump version to 0.12.6

#### October

#### November

  - [27] v0.12.7.0-aeon Merge pull request #78 from stoffu/aeon-bump-0.12.7, bump version to 0.12.7
  - [30] v0.12.8.0-aeon Merge pull request #78 from stoffu/aeon-bump-0.12.7, bump version to 0.12.7

#### December

  - [4] Community meeting

### 2019

#### January

  - [8] Aeon added to Bisq's official release: https://github.com/bisq-network/bisq/releases/tag/v0.9.2

#### Feburary


















