# Honestvote

## Project Abstract
_Honestvote is a former startup that I worked with. The project and its corresponding company have both been scrapped. The goal of the company was to create an election system using blockchain to deliver decentralized, anonymous, and transparent voting. It uses separate elections and the institutions behind them to validate each other, constantly checking for tampering. It uses separates nodes that can apply to become validators to start elections. Voters register their vote, which is then encrypted and called a transaction._ 

## Project Relevance
_This project includes a lot of the key concepts targeted in the educational goals. It includes object-oriented design, test driven development, design patterns, access to database, XML, and more. OOD will be implemented with various aspects of the nodes. Throughout my work in the internship I had to test by creating objects of votes, only continuing my development once I have thoroughly tested each section. With so many parts to the codebase and so many potential users, it is essential to use design patterns to keep a clean and effective codebase. Honestvote also uses the MongoDB, hence we will be as well. The code is maintained in Github allowing for version control. The issue tracking was done in Jira, but it can be converted to Github as well._

## Conceptual Design
_Our proposed contribution will have to do with working on different aspects of the voting and security features. These systems have different optimizations and features that need to be added. This includes security features to prevent tampering. Specifically, this will deal with working with MongoDB to store the transactions and nodes to their corresponding elections. This will deal with working with interesting new technologies like ring signatures for security. The codebase will be mainly comprised of Golang._

## Background

<https://github.com/jneubaum/honestvote>

***Building***
- There is a build folder that holds everything needed to build. All of the necesary imports are held there.
- You must download Golang and set it up appropriately. 
