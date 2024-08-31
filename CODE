// Initialize an empty array to store NFTs
const arr = [];

// Function to mint a new NFT
function mintNFT(name, religion, gender, age, height) {
    const obj_nft = {
        "Name": name,
        "Religion": religion,
        "Gender": gender,
        "Age": age,
        "Height": height,
    };
    arr.push(obj_nft);
    console.log("Name: " + name);
}

// Function to list all NFTs and their metadata
function listNFTs() {
    for (let i = 0; i < arr.length; i++) {
        console.log("\nNFT ID: " + (i + 1));
        console.log("Name: " + arr[i].Name);
        console.log("Religion: " + arr[i].Religion);
        console.log("Gender: " + arr[i].Gender);
        console.log("Age: " + arr[i].Age);
        console.log("Height: " + arr[i].Height);
    }
}

// Function to get the total number of NFTs minted
function getTotalSupply() {
    return arr.length;
}

// Mint some NFTs
mintNFT("Keshav", "Hinduism", "Male", "20", "6.7");
mintNFT("Aniket", "Hinduism", "Male", "22", "5.9");
mintNFT("Ekampreet", "Sikhism", "Female", "18", "6.3");
mintNFT("Ishan", "Christian", "Male", "19", "5.8");

// List all NFTs and print the total number of NFTs
listNFTs();
console.log("\nNumber of NFTs created is: " + getTotalSupply());
