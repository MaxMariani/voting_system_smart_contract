
# Decentralized Voting System Smart Contract

A simple decentralized [Voting](https://en.wikipedia.org/wiki/Voting) system using solidity's blockchain technology.


Actors:

- Manager:  address that created the smart contract, can manually change the current voting phase.
- Voter: address that registered as a Voter during the REGISTER phase,  person who votes or has the right to vote at an election.
- [Candidate](https://en.wikipedia.org/wiki/Candidate): address that registered as a Candidate during the REGISTER phase.


# Behaviors:

- The manager can change the current voting phase (REGISTER, VOTE, END).
- The manager can register as a Voter and Candidate during the REGISTER phase.
- An address can register as a Voter during the REGISTER phase, and can vote a Candidate during the VOTE phase. Each voter can only vote once.
- An address can register as a Candidate during the register phase, and can be voted by Voters during the voting phase. 
- An address can be both a Voter and Candidate at the same time.
---
- If an address tries to register as a Candidate or a Voter outside the register phase, the transaction will be reverted.
- If another address outside the Manager tries to change the votign phase, the transaction will be reverted.



## Running the smart contract

You can run the SC by using Remix: https://remix.ethereum.org/

## Support & Feedback

For support, email wmaxmariani[at]gmail.com .


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/max-mariani-developer/)



