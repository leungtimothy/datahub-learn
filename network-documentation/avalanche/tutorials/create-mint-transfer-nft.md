---
description: 'Learn how to create, mint, and transfer NFTs on Avalanche.'
---

# Create, Mint and Transfer NFTs with the Avalanche Wallet

## Prerequisites

In preparation for the tutorial, we will need to have some images on hand for testing the upload to Avalanche wallet. Please refer to the documentation for more information on the Avalanche wallet,[here](https://docs.avax.network/).

## Introduction

NFT is an interesting term nowadays, in more technical terms NFT collectible is called ERC721 token. Please refer to the below link to learn more about [ERC-721 token](https://ethereum.org/en/developers/docs/standards/tokens/erc-721/). It is a form of “art” that can be a picture, tweet, audio, etc in a broader perspective. A non-fungible token \(NFT\) is a unit of data on a digital ledger called blockchain, where each NFT represents something unique item, that can’t be interchanged. This enables many use cases that would be impossible with interchangeable tokens, like utility, proof of ownership, and a unique asset transaction history.

## Create NFTs

### Create New Wallet

Go to [Avalanche Wallet](https://wallet.avax.network/) and click on create a new wallet.

![](../../../.gitbook/assets/create-new-wallet.png)

### Generate Key Phrase

Next, click the "Generate Key Phrase" button, which will display a list of 24 words that you will need to save in a secure location. This list of words is used to access your account, so do not share it with anyone!

![](../../../.gitbook/assets/generate-new-key.png)

![](../../../.gitbook/assets/your-key-phrase.png)

### Verify And Access Wallet

Once you have saved or written down the keywords in a secure location, click the checkbox to enable the "Access Wallet" button. Clicking this button displays the Verify Mnemonic modal window. Complete the phrase to verify that you have the correct words.

![](../../../.gitbook/assets/verify-key-phrase.png)

Now, you can access your account. Click access and you will be directed to the account window.

![](../../../.gitbook/assets/access-wallet.png)

In your avalanche wallet window, you will see- Balance, Assets, Wallet Address, Transaction & Transaction History \(as shown in image\).

![](../../../.gitbook/assets/avalanche-wallet.png)

On the left sidebar are the other activity tabs: Send, Earn, Cross-chain, Studio, Activity, Manage keys, and Advanced.

## NFT Studio on Avalanche Wallet

To make experimenting with the creation and exchange of NFTs easier, the [Avalanche Wallet](https://wallet.avax.network/)! has a built-in NFT Studio, where you can create NFTs as assets that Avalanche calls Collectibles. Collectibles can be generic NFTs with a picture and a description, or custom NFTs with payloads containing JSON, custom URL, or UTF-8 data. You can create them using a simple point and click interface, enabling you to go from concept to sending NFTs to your friends within minutes. No technical knowledge is required.

To access the **NFT Studio**, log into your Avalanche Wallet, and on the left side select **Studio**:

This will open the NFT Studio. There you have two options: **New Family**, for the creation of a new family of NFTs, and **Mint Collectible** for creating new assets in existing families. We need to create our first family of NFTs, so click **New Family**.

## Create an NFT Family

There you will be asked to enter the name of your collectible family, as well as a symbol \(ticker\). Names do not have to be unique.

## Mint NFTs

Before minting, Go to the Studio tab. Below the heading "Collectibles" are two sections, "new family" and "mint collectibles".

![](../../../.gitbook/assets/avalanche-studio.PNG)

Click on Studio, where you can create a new family of collectibles if you have not yet done so.

![](../../../.gitbook/assets/create-new-family-studio.png)

You can use the TxID to look up the transaction on the Avalanche block explorer. Besides the name and the ticker, you will need to enter a **Number of Groups**, which is how many distinct collectibles the newly created family will hold. Choose carefully, because once created the parameters of the collectible family cannot be changed.

To create a new mint, provide a name, a code, and several groups. Note that a fee of 0.1 AVAX will be deducted from your balance to mint. For testing, you can use the Fuji testnet. You will need to switch networks in the Avalanche wallet UI. Once you are on the Fuji testnet, it is possible to get AVAX for testing from the official faucet.

To give it a test, follow below steps:

![](../../../.gitbook/assets/change-network-to-fuji.png)

Go to the AVAX faucet at [here](https://faucet.avax-test.network/)!

![](../../../.gitbook/assets/avax-faucet-testnet.PNG)

Paste the address of your wallet \(which you can copy from the Avalanche wallet UI\) into the text input and pass the CAPTCHA to receive 2 AVAX tokens.

Select the family we have just created. You will be presented with a form to fill out with the parameters of the new collectible:

![](../../../.gitbook/assets/mint-collectibles.png)

Press **Back to Studio** to return, and we're ready to create our first collectibles. Press **Mint Collectible**. but if minting is not supported, then you need to create a new collectible family as shown below.

![](../../../.gitbook/assets/wallet-avax-network.png)

That is an NFT that has a Title, URL for the image, and a Description. Enter the required data, and the Quantity, which will determine how many copies of the collectible will be created. As before, enter the data carefully - you won't be able to change anything once collectibles are minted. You will see a preview of the data where you can check how your collectible will look.

If you would like to have something else besides a picture collectible, select **Custom**.

![](../../../.gitbook/assets/nft-studio-05-custom.png)

A custom collectible can contain an **UTF-8** encoded string, an **URL**, or a **JSON** payload. The size of the data cannot exceed 1024 characters.

After you enter and check the data, press **Mint** to create the collectible. Transaction fees will be deducted from your wallet, and a newly created collectible will be placed in your wallet.

## See your collectibles

An overview of your collectibles is always visible at the top of the screen, along with your balances.

![](../../../.gitbook/assets/avalanche-balance.png)

To see your collectibles in more detail, select **Portfolio** from the left-hand side menu. You will be presented with a screen showing all of your assets, with tokens selected by default. Change the selection to **Collectibles** by clicking the corresponding tab.

![](../../../.gitbook/assets/collectible-coin.png)

For each Generic collectible, a picture will be shown, along with the title, and the number indicating how many copies of the collectible are in your portfolio. Hovering over the collectible with your pointer will show the detailed description:

If you select a collectible by clicking on it, you will see which group it belongs to, its quantity, along with the **Send** button.

## Transfer NFTs

To send your collectible to someone, either click the **Send** button on the selected collectible in the Portfolio, or navigate to the **Send** tab on the left-hand side menu, and click **Add Collectible**:

![](../../../.gitbook/assets/send-nft-different-address.png)

You will be presented with a menu to select a collectible you wish to send.

![](../../../.gitbook/assets/pikachu-coin-wallet-address.png)

You can send multiple collectibles in a single transaction. Clicking the label on the collectible will let you edit the number of copies you wish to send. You can send multiple families and collectible types in a single transaction.

![](../../../.gitbook/assets/send-nft-to-different-wallet.png)

When you have entered the destination address, and optionally entered the memo text, press **Confirm** to initiate the transaction.

![](../../../.gitbook/assets/transaction-history.png)

After pressing **Send Transaction** it will be published on the network, and the transaction fee will be deducted from your balance. Collectibles will be deposited into the destination address shortly after.

## Summary

Now, you should know how to create families of collectible NFTs, mint NFTs in groups, and send them to other addresses. Have fun with it! If you would like to know the technical background of how NFTs work on the Avalanche network or would like to build products using NFTs, please check out this [Avalanche NFT tutorial](https://learn.figment.io/network-documentation/avalanche/tutorials/creating-an-nft-part-1)!.

If you had any difficulties following this tutorial or simply want to discuss Avalanche tech with us you can [**join our community today**](https://community.figment.io/) or [**Join our discord channel**](https://discord.gg/fszyM7K)!

## About the author

[Devendra Yadav](https://community.figment.io/u/dev.koold)

## References

This tutorial is based on the official [Avalanche Documentation](https://docs.avax.network/build/tutorials/smart-digital-assets/wallet-nft-studio).

