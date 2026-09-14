NFT-Image-Generator
Utility for creating a generative art collection from supplied image layers, especially made for making NFT collectibles.

Click here for example images.
Prerequisites
Clone the repository by opening your Terminal and typing git clone https://github.com/sem/NFT-Image-Generator.git.
Install the dependencies pip3 install -r requirements.txt.
How to use
Get an API key from Pinata.
Open config.json and put the JWT (Secret access token) in api_key.
Adapt the config to your liking and make sure there is a sequential number at the beginning of each folder to represent the order of layers.
Run main.py.
File structure
Before you start, make sure your file structure looks something like this:

NFT-Image-Generator/
├─ main.py
├─ config.json
├─ 1 background/
│  ├─ red.png
│  ├─ green.png
│  ├─ blue.png
├─ 2 body/
│  ├─ female.png
│  ├─ male.png
│  ├─ zombie.png
├─ 3 eyes/
│  ├─ sun_glasses.png
│  ├─ normal_eyes.png
│  ├─ vr_glasses.png
Features
 Generate metadata for direct use on OpenSea.
 Being able to update the image URL after the metadata is created.
 Automatically upload images and metadata to Pinata.
 Ensure that no duplicate images will appear in the collection.
 Create a .GIF profile picture for your collection.
 Give each image a rarity value.
 Influence rarity by giving layers a weight.
