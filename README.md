1. Home Page: 
    1.1 Show recently listed NFTs 
        // How do we show the recently listed NFTs ?
        // We will index the events off—chain and then read from our database. 
        // Setup a server to listen for those events to be fired, and we will add them to a centralised database
        // TheGraph does this in a decentralized way 
        // moralis does it in a centralized way and comes with a ton of other features. 
        // All our logic is still 100 % on chain. 
        // Its really hard to start a prod blockchain project 100 % decetralized.
        
        1.1.1 If you own the NFT, you can update the listing
        1.1.2 If not, you can buy the listing 

2. Sell Page: 
    2.1 You can list your NFT on the marketplace 
    2.2 Withdraw proceeds from the marketplace


3. Moralis: How do we tell it to listen to our events? 
    3.1. Connect it to our blockchain (hardhat node)
    3.2. Which contract, which events, and what to do when it hears those events.

    Create a new table called "ActiveItem" 
    Add items when they are listed on the marketplace 
    Remove them when they are bought or canceled