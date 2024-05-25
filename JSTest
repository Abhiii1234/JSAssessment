/*
Assessment Requirements
1. Create a variable that can hold a number of NFT's. What type of variable might this be?
2. Create an object inside your mintNFT function that will hold the metadata for your NFTs. 
   The metadata values will be passed to the function as parameters. When the NFT is ready, 
   you will store it in the variable you created in step 1
3. Your listNFTs() function will print all of your NFTs metadata to the console (i.e. console.log("Name: " + someNFT.name))
4. For good measure, getTotalSupply() should return the number of NFT's you have created
*/

// Create a variable to hold your NFTs
let nftCollection = [];

// This function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata,
// and store it in the variable above.
function mintNFT(name, artist, dateCreated, owner, description, rarity) {
    // Create a unique identifier for the NFT
    const id = nftCollection.length + 1;
    
    // Create an NFT object with the metadata
    const nft = {
        id: id,
        name: name,
        artist: artist,
        dateCreated: dateCreated,
        owner: owner,
        description: description,
        rarity: rarity
    };
    
    // Store the NFT object in the nftCollection array
    nftCollection.push(nft);
}

// Create a "loop" that will go through an "array" of NFTs
// and print their metadata with console.log()
function listNFTs() {
    nftCollection.forEach(nft => {
        console.log("ID: " + nft.id);
        console.log("Name: " + nft.name);
        console.log("Artist: " + nft.artist);
        console.log("Date Created: " + nft.dateCreated);
        console.log("Owner: " + nft.owner);
        console.log("Description: " + nft.description);
        console.log("Rarity: " + nft.rarity);
        console.log("------");
    });
}

// Print the total number of NFTs we have minted to the console
function getTotalSupply() {
    return nftCollection.length;
}

// Call your functions below this line

// Mint a few NFTs with unique properties
mintNFT("Sunset Landscape", "Abhigyan", "2024-01-01", "Owner1", "A beautiful sunset over the mountains", "Rare");
mintNFT("Abstract Art", "Pushkar", "2024-02-15", "Owner2", "A mesmerizing piece of abstract art", "Common");
mintNFT("Modern Sculpture", "Rohit", "2024-03-10", "Owner3", "A striking modern sculpture", "Uncommon");
mintNFT("Vintage Portrait", "Anjali", "2024-04-20", "Owner4", "A vintage portrait with historical significance", "Legendary");

// List all NFTs
listNFTs();

// Print the total supply of NFTs
console.log("Total Supply: " + getTotalSupply());
