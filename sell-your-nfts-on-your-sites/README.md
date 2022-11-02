---
description: >-
  The easiest way to sell your NFTs. Stop using centralized NFT marketplaces ! 
  Sell your NFTs on the sites you want ! In a real decentralized way :)
---

# Sell your NFTs on your sites !

You can can create different types of NFT collections inside our NFT Factory:

* **Basic** type collection: **OpenNFTs** (_OpenNFTs generic Collection: anyone can Mint NFTs in this collection!)_
  * You can sell your NFTs on NFT marketplaces as OpenSea
* **Royalties** type collection: **AutoMarket** (_AutoMarket ownable OpenNFTs Collection: own your collection, mint and sell your NFTs with royalties)_
  * You can sell your NFTs directly on your wordpress sites without asking your users to buy on external and centralised NFT marketplaces with dedicated **SHORTCODES**
  * You can even ... sell your NFTs on any websites with our "**BUY SNIPPET**"
  * You can use the standard royalties

Please find a wordpress page example: [https://www.kredeum.org/sardaigna/](https://www.kredeum.org/sardaigna/) that has been created with wordpress kredeum shortcodes, displaying automatically NFT images and then allowing users to sell and buy NFTs directly on this wordpress page !

<figure><img src="../.gitbook/assets/Screenshot 2022-11-02 at 23.41.25.png" alt=""><figcaption><p>Above Wordress page back office with Kredeum shortcodes</p></figcaption></figure>



<figure><img src="../.gitbook/assets/Screenshot 2022-11-02 at 23.16.24.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot 2022-11-02 at 23.16.37.png" alt=""><figcaption><p>Above wordress page displaying NFT ready to sell and buy !</p></figcaption></figure>

You can also add the following code (Buy snippet) in any of your web pages ! It will automatically display the NFT and Sell / Buy button for web users :)

```
<div class="kre-buy-front" chainid="137" address="0xafA2517fA3e9C64FBA97F8D0F5773ac5a2C79255" tokenID="1" platform="buy-external">
<script defer src="https://beta.kredeum.com/assets/kredeum-nfts.js"></script>
<script>
var newLink = document.createElement("link");
newLink.href = "https://beta.kredeum.com/assets/kredeum-nfts.css";
newLink.rel = "stylesheet";
newLink.type = "text/css";
document.getElementsByTagName("head")[0].appendChild(newLink);
var newLink2 = document.createElement("link");
newLink2.href = "https://beta.kredeum.com/assets/css/front.css";
newLink2.rel = "stylesheet";
newLink2.type = "text/css";
document.getElementsByTagName("head")[0].appendChild(newLink2);
</script></div>
```

&#x20;

BUILD you own NFT Marketplaces !
