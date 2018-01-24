<div style="text-align:center;width:100%">
<img src="https://raw.githubusercontent.com/nekonium/nekonium.github.io/master/nekonium.png" width="50%"/>
</div>
<br/>
<br/>

# Introduction
Nekonium is a *Distributed Application Platform* forked from <a href="https://ethereum.org/">**Ethereum**</a>. This project was initalized on July 2017 to propose an Ethereum Clone to Japan, and also to experience & utilize it's  functionalities.  We hope that many will gain knowledge through usage of this platform.

Nekonium is developed and operated by the **Nekonium Project**. Unlike other various decentralized currencies, Nekonium is not fit for speculation, and we would like to warn that chances for profit from mining or investment are low.

### Disclamer
Nekonium Project holds no responsibility for any damage and loss resulting from usage of this platform and all related software - including issues related to loss of balance. You are solely liable and responsible for all consequences.


# Specification
Due to the clone nature of Nekonium, it's internal specs are mostly the same as Ethereum.　The coin/currency in circulation within this platform is named Nekonium (**NUKO** for short), and mining is possible via POW.

```
* Name nekonium
* Unit NUKO
* Premine 12,448,421 NUKO
* Mining Limit None
* TCP/UDP Port 28568
* UDP　Port 28566
* RPC(HTTP) 8293
* RPC(WS) 8294
* Reward 7.5 NUKO
* BlockTime
*   0 - 0  Block      Frontier 19sec
*   - 7776 Block      Homestead 10-20sec target DiffBoundDiv=512
*   7777 - Block      Homestead 19-29sec target　Without Exp BOM DiffBoundDiv=1024
* GasLimitBoundDivisor　1024
* DifficultyBoundDivisor 1024
```

<a href="https://nekonium.github.io/premine.html">&gt;&gt;Premine details&lt;&lt;</a>


### Startup Schedule

* <s>Closed Beta (～6/28)</s> **Done**
* <s>Open Beta (6/29～)</s>　**Done**
* ✅Release

Officially released, since 20000 Blocks have been mined. Please have fun!
<s>We're also doing giveaways in Discord, join in to get 100 NUKOs</s> **Done**



# Downloads

## gnekonium
<a href="https://github.com/nekonium/go-nekonium">https://github.com/nekonium/go-nekonium</a>

go-ethereum(geth)を基にしたnekoniumのクライアントソフトウェアです。

### マイニング
go-nekoniumリリースからバイナリ、またはソースコードをダウンロードしてください。ソースからビルドする場合はEthereumの取説のgethをgnekoniumに読み替えて頑張ってください。 簡単な始め方はこちらをご覧ください。<a href="https://nekonium.github.io/getstarted.html">Get Started</a>

gnekoniumのコンソールからマイニングすることができます。

    $gnekonium console
    :
    :(いろいろたくさん)
    :
    >miner.start(2)

## ウォレットアプリケーション

<a href="https://github.com/nekonium/mist">https://github.com/nekonium/mist</a>

Ethereum Mistベースのウォレットです。マイニングはできません。現在はオートアップデートが機能しませんので、gnekoniumを起動してから使用してください。

<img src="https://github.com/nekonium/nekonium.github.io/blob/master/img/mistpreview.png?raw=true" width="50%"></img>

## モバイルウォレット
<a href="https://play.google.com/store/apps/details?id=org.nekonium.androidnuko">https://play.google.com/store/apps/details?id=org.nekonium.androidnuko</a>

Android用のモバイルウォレットです。

<img src="http://nekonium.github.io/pr/imgs/cp01-1.png" width="33%"/>

# サービス
## Wallet
* <a href="http://www.nukowallet.com/">http://www.nukowallet.com/</a> officiall webwallet

## Block exproler
* <a href="http://explorer.nekonium.org/home/home">http://explorer.nekonium.org/home</a>
* <a href="http://nukoexplorer.oldbeyond.com/">http://nukoexplorer.oldbeyond.com/</a>
* <a href="http://nekonium.network/">http://nekonium.network/</a>


## Pool
* <a href="http://nuko.oldbeyond.com/">http://nuko.oldbeyond.com/</a>
* <a href="http://nuko.ftlpool.com/#/">http://nuko.ftlpool.com/#/</a>
* <a href="http://nuko.coinminer.space/#/">http://nuko.coinminer.space/#/</a>
* <a href="http://www.nekonium-pool.com/">http://www.nekonium-pool.com/</a>
* <a href="http://nuko.cep-k.work/">http://nuko.cep-k.work/</a>
* <a href="http://nuko.mofumofu.me/">http://nuko.mofumofu.me/</a>
* <a href="https://minerpool.net/">https://minerpool.net/</a>

## Faucet
* <a href="http://nuko.oldbeyond.com/#/faucet">http://nuko.oldbeyond.com/#/faucet</a>
* <a href="http://namuyan.dip.jp/nekoniumFaucet.php">http://namuyan.dip.jp/nekoniumFaucet.php</a>
* <a href="https://faucet.nekonium.net/">https://faucet.nekonium.net/</a>

## SNS
* Twitter <a href="https://twitter.com/NekoniumDev">https://twitter.com/NekoniumDev</a>
* Discord channel <a href="https://discord.gg/C8mJg44">https://discord.gg/C8mJg44</a>
* ASKmona <a href="http://askmona.org/5387">http://askmona.org/5387</a>
* Bitcointalk <a href="http://askmona.org/5387">https://bitcointalk.org/index.php?topic=2012213.0</a>

## etc
* <a href="http://stats.nekonium.io/">http://stats.nekonium.io/</a> Network status
* <a href="http://stuff.cuppadev.co.uk/nuko-report.html">http://stuff.cuppadev.co.uk/nuko-report.html</a> rich list
* <a href="https://minerpool.net/pools/nekonium/">https://minerpool.net/pools/nekonium/</a> Active Pool list


## QR generator
* <a href="http://qr.nekonium.info/">http://qr.nekonium.info/</a>
* <a href="https://nuko-qr.azurewebsites.net/">https://nuko-qr.azurewebsites.net/</a>


## Contract-Dev
* Browser-Solidity IDE (NEW) <a href="http://nekonium.org/browser-solidity/01.85884478a57de99508250b0e1b625e9afd1e7eaf">http://nekonium.org/browser-solidity/02/</a>
* (OLD) <a href="http://nekonium.org/browser-solidity/01.85884478a57de99508250b0e1b625e9afd1e7eaf">http://nekonium.org/browser-solidity/01.85884478a57de99508250b0e1b625e9afd1e7eaf</a>
* <a href="https://nekonium.github.io//browser-solidity/solidity.JP.html">Nekoniumのコントラクトの作り方</a>

# 配布について
Nekoniumは採掘で手に入れることもできますが、事前に確保したNekoniumの配布も実施しております。ネットワーク維持のためのマイニングや常設ノードの起動、その他サービス（プールやファーセット）の設置にも報酬があります。配布と報酬については<b>Premineについて</b>を参照してください。

<a href="https://github.com/nekonium/nekonium.github.io/blob/master/premine.md">Premineについて</a>

# Resources

* <a href="https://github.com/nekonium/nekonium.github.io/blob/master/resources.image/resources.md">Logo/Images etc</a>
* <a href="https://github.com/nekonium/nekonium.github.io/blob/master/software.md">Source codes</a>
* <a href="https://github.com/nekonium/nekonium.github.io/blob/master/documents.md">Documents</a>

# 開発メンバー

* てばさき
* ふとん
* hxcoin
* なむやんぐ
* かばやき
* 7Zz
