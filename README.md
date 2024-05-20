# JavaScript-Assessment

# VIDEO LINK

https://www.loom.com/share/dd0a4c186932432cad96f142cf7a04f8

# SUMMARY OF MY VIDEO
Hi everyone, my name is Renzo and in this video, I will be going through my JavaScript assessment code. I will start by defining an array and naming it. Then, I will explain how to create an object inside the parameters and assign metadata values to it. Next, I will show you how to store variables in the created object. After that, I will demonstrate a loop and explain how to retrieve the total supply. Finally, I will provide an output example.

## MY CODE

````javascript
  // create a variable to hold your NFT's
const NFTs = []

// this function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata, 
// and store it in the variable above.
function mintNFT (_name, _watchbrand, _carbrand, _country) {
    const NFT = {
        "name": _name,
        "watchbrand": _watchbrand,
        "carbrand": _carbrand,
        "country": _country
    }
    NFTs.push(NFT);
    console.log("Minted " + _name);
}

// create a "loop" that will go through an "array" of NFT's
// and print their metadata with console.log()
function listNFTs () {
  for(let i = 0; i < NFTs.length; i++) {
    console.log("\nID: \t\t" + (i + 1));
    console.log("Name \t\t" + NFTs[i].name);
    console.log("Watch brand \t\t" + NFTs[i].watchbrand);
    console.log("Car Brand \t\t" + NFTs[i].carbrand);
    console.log("Country \t\t" + NFTs[i].country);
}
}

// print the total of number of NFTs we have minted to the console
function getTotalSupply() {
  console.log(NFTs.length);
}

// call your function below this line
mintNFT("Richard", "Rolex", "Lamborgini", "USA");
mintNFT("Wilson", "Rolex", "Ferrari", "Philippines");
mintNFT("Agustino", "Rolex", "Toyota", "Japan");
mintNFT("Renzo", "Rolex", "BMW", "China");
listNFTs();
getTotalSupply();

````


# CHAPTERS
###### 0:00 Introduction
###### 0:24 Creating the Object
###### 1:00 Storing Variables
###### 1:56 Loop Explanation
###### 2:25 Retrieving Total Supply

## Author

Renzo Tugano BSIT
@RenzsTugano1

# LICENCE
Copyright (c) 2024 RenzsTugano1

