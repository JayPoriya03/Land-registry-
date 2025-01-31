LandRegistry Smart Contract
The LandRegistry smart contract is a decentralized land ownership system built on Ethereum. It allows users to register land parcels, transfer ownership, and retrieve land details securely and transparently.

Features:
Register Land: Users can register new land parcels by providing an ID, location, and area.
Ownership Transfer: Landowners can transfer ownership of their registered land to a new owner.
Retrieve Land Details: Anyone can check land details, including ID, location, area, owner, and registration status.
Check Registration Status: Verify whether a land parcel is registered.
Smart Contract Details:
Uses Solidity ^0.8.0 and follows the MIT License.
Implements struct to define land properties.
Uses a mapping to store registered land information.
Emits events for LandRegistered and OwnershipTransferred for transparency.
Ensures only the current owner can transfer ownership.
This contract enhances security and trust in land ownership management through blockchain technology. 🚀
