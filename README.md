### ERC20
| name | address | contract |
|------|---------|----------|
| USDK | 0xd2137Fdf10bD9e4E850C17539eB24cfe28777753 | KromeStable |
| KROME | 0xfbD0314D55EAb31C9FC0b2D162748017F1bc7b85 | KromeShares |

### DAO
| name | address | contract |
|------|---------|----------|
| timelock | 0x2c9498dcDaaEC707837f0d8f67c443d743D240D9 | Timelock |
| tokenSwapHelper | 0x74e8493eE43d63b32f80cB625c19492C361Cb8cB | ClaimswapHelper |
| collateralRatio | 0xf3B86B364269FFA3c74038A570a4AbF0aae950B3 | UsdkCollateralRatio |
| usdkPool(V5) | 0x575ec8a3737512A9Dc408522539915Aa86BbDaE9 | UsdkPoolV5 |
| amoMinterRegistry | 0x0f4A616bE05D0F28bA724bFE80a64062E2aa262A | AMOMinterRegistry |
| amoMinter(V2) | 0x50e27146675B2c48620dBAAbC501c5a302A173DE | UsdkAMOMinterV2 |
| veKROME | 0x36d83CC762F614970daeb1909141Fc5ddA9683D5 | veKrome |
| smartWalletWhitelist | 0x61d73C8B76D7E84fd7D3eA4212Dce01b0FEf0dc3 | SmartWalletWhitelist |
| veKromeYieldDistributorV5 | 0xBf3B5537cCe7Fc4a223f3F4Ee0538A75a640C9dc | veKromeYieldDistributorV5 |
| fxs1559 | 0xAD7f46e65dCF9d30fC7827d72f2A1D392e0cB0D9 | FXS1559_AMO_V3 |
| veDelegation | 0x8A2308371F7A405A0EA18B8f11e5239473b4F66b | VotingEscrowDelegation |
| delegationProxy | 0x28D2571fCa0Bdb90B8F443F666015B75b82837d9 | DelegationProxy |
| manualGaugeController | 0xae1E24c20edc3D52E7A706783dDd898937A3df90 | ManageGaugeController |
| gaugeRewardDistributor | 0x13330d982B7f024A98257037bA23f9C810586114 | GaugeRewardDistributor |
| boostController | 0x58fe5CF1247E2FCD00174547DBab34e7fb75fE1E | StakingBoostController |
| kromeRewardDelegator | 0x69602Cda969091c0D86Fa75b3b59B2f81e241C03 | KromeRewardForStakingDelegator |
| kromeRewardDelegatorV2 | 0xd424737Af0F5aE445EE5deca39d997C374571ECc | KromeRewardForStakingDelegatorV2 |
| EklipseDelegator | 0xCcb313446ef69307fbA478a5B74d0AF8Fc92D31D | EklipseDelegator |

### AMO
| name | address | contract |
|------|---------|----------|
| fxs1559 | 0xAD7f46e65dCF9d30fC7827d72f2A1D392e0cB0D9 | FXS1559_AMO_V3 |
| external wallet AMO USDT | 0x63Fc79C34abAA652AbC14238A6cE19Fd241499f9 | ExternalKUSDTWalletAMO |
| external wallet for USDT | 0x2f2e92cDf069f8AF3828aB120B2379B3f3B36f7b | (not contract, EOA) |

### ORACLES
| name | address | contract |
|------|---------|----------|
| klayPriceOracle | 0xFEb4F2B1Af842185D5B5C8A87fb8350762CEf57E | (external contract) |
| usdkPriceOracle | 0xF813D6bA69A9e1B71751b546Aed0e76Ff6DeB448 | UsdkPriceOracle |
| kromePriceOracle | 0xBAAA80952AE1040DF50Ec9494Da621AD87834Ed0 | KromePriceOracle |

### LP tokens
| name | address | contract |
|------|---------|----------|
| Claimswap USDK-KLAY | 0x433db089d5237748ee19d06b29372deb67108353 | (external contract) |
| Claimswap USDK-KROME | 0x5f9942e8769591e7a2a18f6728ff128d6a08723d | (external contract) |
| Kokonutswap USDK-4NUT | 0x0fd58c80fbb9728093c1ea041fcfd3ee723ff696 | (external contract) |
| Eklipse USDK-3Moon | 0xc4ACf4ddd4838E9A727cCDb75ae62Af1706a7173 | (external contract) |
| Claimswap USDK-KUSDT(deprecated) | 0x1437459e1f932d86ee97ab2dfac058fa0a60769c | (external contract) |

### Staking Pools Beacons
| name | address | contract |
|------|---------|----------|
| Treasury reward | 0xFE31E1c42e0A4B99fCDCA5884B2bc1d688444863 | StakingRewardComptrollerV4 |
| LP migration - stable KSLP Pair | 0x472Fbc7b143F25CfAE21771cb011a07580bfFdcf | LpMigrationPoolKSLP_Stable |

### Staking Pools
| name | address | contract |
|------|---------|----------|
| Claimswap USDK-KLAY Pool | 0xc19B3652D26Deb9263aD985aA0e367015D641e68 | TreasuryUsdkUniswapPairV3 |
| Claimswap USDK-KLAY Reward | 0x15e14201D5A86d648981cCDdD1f8Fac29517050c | StakingRewardComptrollerV3 |
| Claimswap USDK-4NUT Pool | 0xC88DBf0a0d446271F1957de75fCdD561D71A7738 | TreasuryUsdkI4IPool |
| Claimswap USDK-4NUT Reward | 0xe282b656Fc45415487D20B8cFB0D68ad692c77D0 |StakingRewardComptrollerV4 |
| Claimswap USDK-KROME Pool | 0xcEF300dc1120845eDD26874Fe4d790868B783177 | TreasuryUsdkUniswapPairV3 |
| Claimswap USDK-KROME Reward | 0x0FFCA580690fc15fA8bE07c26bbbD2dC18f555DA | StakingRewardComptrollerV3 |
| Claimswap USDK-3Moon Pool | 0xEb5DFaDa43BC492aCa2D74071fDe686CB4Ef27f9 |TreasuryUsdkEklipsePool |
| Claimswap USDK-3Moon Reward | 0xa200e9876AA6EBd405777B211ca8C7011BA41c95 | StakingRewardComptrollerV3 |

### LP Migration
| name | address | contract |
|------|---------|----------|
| LP migration KSLP KLAY-oUSDT pool | 0x9f883485143880d51851D6F534dbdFA964756DA8 | BeaconProxy<br />0x472Fbc7b143F25CfAE21771cb011a07580bfFdcf |
| LP migration KSLP KLAY-oUSDT reward | 0xC1C03535f0B9058e00C11Aa79430F7C9Bd26E37B | BeaconProxy<br />0x472Fbc7b143F25CfAE21771cb011a07580bfFdcf |
| LP migration KSLP oETH-oUSDT pool | 0x9f883485143880d51851D6F534dbdFA964756DA8 | BeaconProxy<br />0x472Fbc7b143F25CfAE21771cb011a07580bfFdcf |
| LP migration KSLP oETH-oUSDT reward | 0xC1C03535f0B9058e00C11Aa79430F7C9Bd26E37B | BeaconProxy<br />0x472Fbc7b143F25CfAE21771cb011a07580bfFdcf |
| LP migration KSLP WEMIX-oUSDT pool | 0x9f883485143880d51851D6F534dbdFA964756DA8 | BeaconProxy<br />0x472Fbc7b143F25CfAE21771cb011a07580bfFdcf |
| LP migration KSLP WEMIX-oUSDT reward | 0xC1C03535f0B9058e00C11Aa79430F7C9Bd26E37B | BeaconProxy<br />0x472Fbc7b143F25CfAE21771cb011a07580bfFdcf |
| LP migration KSLP oXRP-oUSDT pool | 0x9f883485143880d51851D6F534dbdFA964756DA8 | BeaconProxy<br />0x472Fbc7b143F25CfAE21771cb011a07580bfFdcf |
| LP migration KSLP oXRP-oUSDT reward | 0xC1C03535f0B9058e00C11Aa79430F7C9Bd26E37B | BeaconProxy<br />0x472Fbc7b143F25CfAE21771cb011a07580bfFdcf |
| LP migration KSLP oWBTC-oUSDT pool | 0x9f883485143880d51851D6F534dbdFA964756DA8 | BeaconProxy<br />0x472Fbc7b143F25CfAE21771cb011a07580bfFdcf |
| LP migration KSLP oWBTC-oUSDT reward | 0xC1C03535f0B9058e00C11Aa79430F7C9Bd26E37B | BeaconProxy<br />0x472Fbc7b143F25CfAE21771cb011a07580bfFdcf |

### Pool manage migrator
| name | address | contract |
|------|---------|----------|
| Pool Management migrator | 0xBc0334c84998778c1BfbcbC470d162732A026Fcb | ManageStakeMigratorV1 |
| Merge stake migrator (old) | 0x94E33005ADD640EA1fCC71a4a9960640af566857 | MergeStakeMigratorV2 |

### Pool migrator
| name | address | contract |
|------|---------|----------|
| erc20PoolMigrator V1 | 0xB9574250167EEe4a2831f60778077Ed334816105 | MigratorTreasury_ERC20 |
| 3MoonTo4NutMigrator V5 | 0x9F2470308400542a451fd2e697baC4d6c1a6e7E3 | MigratorTreasury_3MoonToI4I |
| erc20PoolEklipseMigrator V5 | 0xB36B3b1010A6535ca43B97C40ed90Fe5114C657F | MigratorTreasury_USDT2Eklipse |

## Deprecated
| name | address | contract |
|------|---------|----------|
| manualGaugeController | 0x951d5B0d742fA75E4934820a815cf9bCdC0d2da6 | ManualGaugeController |
| boostController | 0xeeA66684D6f77E486E242c9EF3Aa434eb49Fd615 | StakingBoostControler |
| veKromeYieldDistributorV4 | 0xAc29EAdDc6e37B7dF5133adA1a0F8119EbfFB948 | veKromeYieldDistributorV4 |
| erc20MergeStakeMigratorV1 | 0x94E33005ADD640EA1fCC71a4a9960640af566857 | MergeStakeMigratorV1 |
| usdkPoolV3 | 0x68F55EAdC923f4c456c8335bc1fa1E4ae15181F9 | UsdkPoolV3 |
| usdkPoolV4 | 0x8D4aBc27e7eaB29c6780e11bfCa98B631F4B7e15 | UsdkPoolV4 |
| amoMinterV1 | 0x2ddEb42c3bc39B8DffB03381f5909e8C324dB49E | UsdkAMOMinter |

### Staking Pools (deprecated)
| name | address | contract |
|------|---------|----------|
| Claimswap USDK-KLAY Pool V1 | 0x33FFF28cFDaBbd6De09635E51aCEF4382A1c1795 | TreasuryUsdkUniswapPair |
| Claimswap USDK-KLAY Reward V1 | 0x8CA15EC4b22f49C3E484A0d71B08396bD914FAc0 | StakingRewardComptroller |
| Claimswap USDK-KUSDT Pool V1 | 0x2707B65afc08e8E1c02472f5D8b735b4dd8Dd1d0 | TreasuryUsdkUniswapPair |
| Claimswap USDK-KUSDT Pool V2 | 0x1D09c9f6C74a3e3cFE54f99A97211f20244a3cEb | TreasuryUsdkUniswapPairV2 |
| Claimswap USDK-KUSDT Reward V1 | 0xbc6481d7Cf58dbC683e0006D15a15a018700Ee83 | StakingRewardComptroller |
| Claimswap USDK-KUSDT Reward V2 | 0x6C7A68B44bB6aA4C774916654D4eE3CE4A34664A |StakingRewardComptrollerV2 |
| Claimswap USDK-KROME Pool V1 | 0x355e58ED5708De8e98e3240e4F98671170822153 | TreasuryUsdkUniswapPair |
| Claimswap USDK-KROME Reward V1 | 0x40B1A247a91D5678B76E73f1445BE61E78494bcA | StakingRewardComptroller |
| Claimswap USDK-KLAY RewardV2 | 0x68A0eF1B1aaaec0b42936ef8bfcD01AfF526438B | StakingRewardComptrollerV2 |
| Claimswap USDK-KUSDT RewardV2 | 0x5cDF3E6782dA06f2d7076676bdE85Be6842541B5 |StakingRewardComptrollerV2 |
| Claimswap USDK-KROME RewardV2 | 0xB9574250167EEe4a2831f60778077Ed334816105 |StakingRewardComptrollerV2 |
