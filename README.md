# EtherShare

[EtherShare](http://ethershare.org) is a project to share information with permanent storage and open access on Ethereum.

> The website is not the only one entry to EtherShare. EtherShare is a DApp. So you can download the html files to your own server or access the contract in other ways.

## Quick Start

There are several optional ways to use EtherShare since it is a DApp.

**Option 1 : Visit the Website**

You can just visit [ethershare.org](http://ethershare.org) or [ethershare.github.io](https://ethershare.github.io) to use EtherShare.  
Please install Metamask or use other Ethereum wallets that supporting DApp browsers. Or you can only view the Shares in the `cache.html`.

**Option 2 : Download the HTML Files**

First, clone the source code from this repository (the HTML files are the same as ethershare.github.io).  
`git clone https://github.com/ethershare/ethershare.git`

Then you can see the HTML files. `cd EtherShare/html/`  and copy the HTML files to the directory of your HTTP server.

Take [XAMPP](https://www.apachefriends.org/) as an example, the files in `EtherShare/html/` should be copied into `C:/xampp/htdocs` or `/opt/xamppp/htdocs/`.

After that, you can visit `localhost` to use EtherShare (Metamask or other Ethereum DApp browsers are also required).

**Option 3 : Use the EtherShareClient**

EtherShareClient is working in progress. For an alpha version in Windows-x64, you can just download and unzip [EtherShareClient-win-x64.zip](https://github.com/ethershare/EtherShareClient/raw/master/EtherShareClient-win-x64.zip) then run the `run.bat`.

**Option 4 : Deploy on Your Private Blockchain**

TBD


## Smart Contracts

The contract addresses are 0xc86bdf9661c62646194ef29b1b8f5fe226e8c97e, 0x475de1f3e1ba5aeefc9fc694852c8fce59b353a1,  0x28daa51dc3d80a951af9c451d174f0c7156c6876, 0x43820f75f021c34ce13ded1595633ed39b79ab47, 0x71de0d9fea931b42297d94cac5ec915410e1da99.

You can find the state of it on [StateOfTheDApps](https://www.stateofthedapps.com/dapps/ethershare).

You can review the source code and trasactions through Ethereum explorer (e.g., Etherscan.io): 

Contract | Address | Explorer
-|-|-
EtherShare | 0xc86bdf9661c62646194ef29b1b8f5fe226e8c97e | [Etherscan](https://etherscan.io/address/0xc86bdf9661c62646194ef29b1b8f5fe226e8c97e) |
EtherShareDonation | 0x475de1f3e1ba5aeefc9fc694852c8fce59b353a1 | [Etherscan](https://etherscan.io/address/0x475de1f3e1ba5aeefc9fc694852c8fce59b353a1) |
EtherShareReward | 0x28daa51dc3d80a951af9c451d174f0c7156c6876 | [Etherscan](https://etherscan.io/address/0x28daa51dc3d80a951af9c451d174f0c7156c6876) |
EtherShareLike | 0x43820f75f021c34ce13ded1595633ed39b79ab47 | [Etherscan](https://etherscan.io/address/0x43820f75f021c34ce13ded1595633ed39b79ab47) |
EtherShareQuery | 0x71de0d9fea931b42297d94cac5ec915410e1da99 | [Etherscan](https://etherscan.io/address/0x71de0d9fea931b42297d94cac5ec915410e1da99) |

You can also review all the source code on `EtherShare/contract/`.

Thanks...