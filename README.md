# MartianMarket

![mars](https://image.shutterstock.com/image-photo/silhouette-astronaut-standing-on-rocky-600w-1049625047.jpg)

The system will be a combination of an ERC721 contract and an Auction contract combined to form the MartianMarket contract to develop a system to raise funds for Martian land development.

The foundation will be able to register new landmarks with their account, minting and creating a new auction for the landmark.
When the `endAuction` function is called, the auction will complete and the token will be transferred to the highest bidder.

The functions of the contract can be designed to have the foundation pay for the most expensive functions like`safeTransferFrom`.
This can be done by putting the token transfer in the `endAuction` function that only the foundation can call.

Each landmark will be a unique ERC721 token, with its own metadata including the landmark `name` and `image` URL.

