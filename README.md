### Shadow Network
Smart Contract Code : https://github.com/0xWick/ShadowNetwork-Backend.git

## Title:
A social network for organizations who prioritize anonymity and privacy (hence the name Shadow Network). With everything a secret organization needs from Encrypted file sharing to secret meeting rooms!

## Motivation: 
This project is built on our motivations of making Web3 anonymous and private for people who value their data but still want to interact with each other in a secure and secret way.

## How to use: (Social Media)
Users can create Syndicates, join other syndicates, post in syndicates. Vote & comments on posts.
Syndicate Creators:  (Soulbound NFTs and Push Notifications)
The founder of syndicate choose who can join the network by minting him a "soul-bound NFTs" (he gets notified via Push Protocol's notifications). Then the user can join the syndicate and post, comment, vote in it.

## Syndicate Members (Secure File sharing - Access Control with NFTs):
Also, Syndicate members can share secret data using (lighthouse SDK) Ninja Sharing - Encrypted File, image, text upload and the other party can decrypt and download it.

## Secret Meeting Rooms:
Each Syndicate has a secret Room (shhhh!). But only members can see and meet in that room. Just like Old School Secret Organizations. Using Huddle01 SDK, they can chat, share files, hold live meetings with cam, even record it and save on IPFS.

## Technologies:
`-> Filecoin/IPFS:` Being used to store On-chain Images, thanks to their robust economic models anyone can take advantage of the best storage network.
-> Huddle01 SDK: Best sdk we used for building our secret meeting rooms, will add NFT gating as soon as they launch it. For now, we are using our own hack to NFT-gate the meeting rooms.
`-> Push Notifications:` On-Chain Notifications using their testnet interface. Users who want to join a Syndicate get a notification when they receive an invite from the Founder of Syndicate. They can check their notifications with Channel Name. And join the Syndicate as soon as they get a Ping(or Push XD) in their Notifications Tab.
`-> Lighthouse SDK:` Everything you need for secret, secure and decentralized file sharing in the Web3 Space. And the cherries(plural) on top were their "Access Control Features". Users can "Token Gate" files shared and only those who "satisfy that On-Chain Condition" can access the file.
