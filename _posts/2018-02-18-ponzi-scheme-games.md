---
layout: post
title: 區塊鏈遊戲的新熱潮：龐氏騙局遊戲
image: https://i.imgur.com/lop42Zv.png
---

在2018年2月10日到17日，一支名為 [**CryptoCountries**](https://cryptocountries.io/) 的 DApp（去中心化應用程式），**七天內的 ETH 交易總額達到了 44000 ETH**，相當於 4200 萬美金，或 12 億新台幣。大幅超越了排名第 2 的老牌賭場 [Etheroll](https://etheroll.com/) （7500 ETH），和排名第 5 的知名養貓遊戲 [CryptoKitties](https://www.cryptokitties.co/)（1750 ETH）。

這當然引起我的好奇心：究竟是多有趣的遊戲才能促成如此可怕的交易量？經過兩天的深入研究，我發現 CryptoCountries 的機制相當簡單，而且類似玩法的遊戲還在不斷湧現，形成一股熱潮。以下就讓我介紹 CryptoCountries 的玩法和我這幾天來的發現。

![dappradar](https://i.imgur.com/9pZvcO8.png)

CryptoCountries 一言以蔽之是一個「**購買虛擬國家，並期待下一個人花更多錢買下它**」的遊戲，一個國家的價格從 0.001 ETH 開始，一個玩家買下它之後便能暫時擁有這個國家，玩家的名字會出現在那個國家的 Owner 欄位，同時價格會上升100%變成0.002 ETH。別的玩家可以付錢給上一個擁有者來買下這個國家，之後價格會再上升100%變成0.004 ETH，等待下一個玩家買下它，一直重複下去。過程中每一個購買者都能獲得100%的收益，而倒霉的最後一隻老鼠則會承受鉅額的虧損。

但每次都增加100%的話，價格很快就會高到「沒有人覺得會有下一個買家願意買單」，因此製作團隊相當貼心的設計了一個機制：隨著價格上升，價格增長的幅度會逐漸下降，當價格超過5 ETH後，增長的幅度便會停在15%。

![CryptoCountries price increase model](https://i.imgur.com/5iOsdOM.png)

現在 CryptoCountries 上面最貴的四個國家依序是日本、香港、中國、南韓。價格最高的日本達到了 709.6 ETH。但美國、俄羅斯等部分國家目前還沒開放購買，也許開發團隊是想等到 CryptoCountries 的人氣更高了才開放吧。

![expensive countries](https://i.imgur.com/lop42Zv.png)

最便宜的幾個國家也有3 ETH以上。（不要問我這些國家在哪裡...）

![cheap countries](https://i.imgur.com/vc7VGgR.png)

台灣的價格目前約 290.8 ETH，排名第9位。

![taiwan](https://i.imgur.com/OLISr2d.png)

最初是誰發明這種玩法的已經很難考證，但據我所知，早在Ethereum問世初期，就有人**用智能合約實作 Pyramid Scheme（金字塔式騙局）** 了，只是一直沒有很明顯的熱潮出現。會到最近才爆發可能是2017年底 CryptoKitties 上線後，人們開始接觸 DApp 和 Metamask，開發者們看到 CryptoKitties 的成功也開始湧入 DApp 圈，所以才在2018年初造成這股風潮吧。

總之**類似的機制已經被大量運用在各種主題上**：
1. 同樣以購買國家為主題的 [World-YouCollect](http://world.youcollect.co/#/marketplace)
2. 以購買twitter名人為主題並號稱會將4%收益給本人的 [Crypto All Stars](https://cryptoallstars.co)
3. 以購買明星為主題的 [CryptoCelebrities](https://www.cryptocelebrities.co)
4. 以購買足球隊和球星為主題的 [WorldCupEther](https://worldcupether.com)
5. 以購買名畫為主題的 [CryptoMasterpieces](https://www.cryptomasterpieces.com) 和 [CryptoArts](https://www.cryptoarts.co/)
6. 以購買政治人物為主題的 [Crypto Politicians](https://cryptopoliticians.co/)

最後，**我自己也照著 CryptoCountries 的合約試做了一個 DApp**，叫 [CryptoRoger](https://roger-wu.github.io/crypto-roger/index.html)（加密版的我XD）。如果你想體驗 CryptoCountries 但覺得價格太高買不下手，可以玩玩看 CryptoRoger，規則跟 CryptoCountries 完全一樣，只是主題從「購買國家」變成「贊助我」，前一個贊助者可以透過後一個贊助者獲利，而我也能獲得2%-5%的開發費用！（目前無法顯示贊助者的位址以外的資訊，贊助者如果想顯示任何資訊在網頁上，歡迎直接聯絡我！）

[![CryptoRoger](https://i.imgur.com/ca7Uh2l.png)](https://roger-wu.github.io/crypto-roger)

**CryptoRoger 網址： [https://roger-wu.github.io/crypto-roger](https://roger-wu.github.io/crypto-roger)**
