# Functions to implement

A list of functions/modifiers that should be included in the NFTmarketplace contract.

# NFT Basics

Create NFT
Buy NFT
Transfer NFT
Burn NFT - send to 0x000000000000000000000000000000000000dEaD

List NFT
Update NFT Listing
Cancel NFT Listing
Set NFT Listing Expiration - allows the NFT owner to set an expiration time on their NFT Listing.

//modifier
Is Listing Expired

# NFT BID

Place Bid - allows a user to place a bid on an NFT
Cancel Bid - allows a user to cancel a bid they have placed on an NFT
Set NFT Bid Expiration

Accept Bid - allows the NFT Owner to accept a bid on their NFT
Decline Bid - allows the NFT Owner to decline a bid on their NFT

Transfer NFT to highest Bidder

Set Minimum Bid Increment
Set Bidder Blacklist
Set Bid Auto Accept - allows the NFT owner to automatically accept any bid that meets or exceeds a preset amount.

Get NFT Current Highest Bid
Get NFT Bid History

//modifier
Is Bid Expired

# NFT Details

Get NFT Details - Listed / Unlited NFT
Get All Listed NFTs

Get Created NFTS
Get Owned NFTs
Get Bought NFTs

# NFT Royalties

Set Royalty Fee - For NFT Creator
Withdraw Royalty Earnings - For NFT Creator

Set Marketplace Fee - For Marketplace Owner
Withdraw Marketplace Earnings - For Marketplace Owner

# Ownership

Transfer Ownership - allows the Marketplace Owner to transfer ownership of the marketplace contract.
