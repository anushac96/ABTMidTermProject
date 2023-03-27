# CPSC 559 - Advance Blockchain Technology

## Mid Term Project

## By Team SAP

## Team members:
1. Anusha Hadagali      CWID: 885451450   Email ID: anusha.hadagali@csu.fullerton.edu
2. Surrajkumar Prabhu Venkatesh     CWID: 885198499   Email ID: surrajkumar2000@csu.fullerton.edu
3. Prashams Omprakash Daulath       CWID: 885582262   Email ID: prash_IND@csu.fullerton.edu
4. Manish Reddy Kambalapally        CWID: 885175679   Email ID: manish.reddy@csu.fullerton.edu  


## Professor

Prof. Wenlin Han, CSU Fullerton: whan@fullerton.edu

## Additional Work

- Updated the user interface.
- Added NFT on Marketplace.
- Deployed it in Goerli network along with localhost

## Project Repo URL
https://github.com/anushac96/ABTMidTermProject.git


# Requirments:
- Metamask account 
- Node.js 

## Setting Up Enviorment:
- Insatll Metamask
- Install Node.js 
- Install Ganache

# Instructions:

## 1. Clone/download the repos 
https://github.com/anushac96/ABTMidTermProject.git

## 2. Configure the index file using
     Change the Zombie ownership in script.js with your own contract ownership address. 

## 3. Verify:
Compile and migrate using 'truffle compile' and 'truffle migrate'
once the initialization is done make sure truffle configuration is correct with the ganache localhost.
   
## 4. Test Run:
Run the server using 'http-server'
The console will show the address
Use that address to open the server

# Features implemented
## 1. Zombie Creation with the name creation
  A prompt is asked for the zombie name and the zombie is created
## 2. Showing the list of zombies created
  Shows the details of the zombies in the order below
  1. Name of the zombie
  2. DNA
  3. Level
  4. Wins
  5. Losses
  6. Ready time
## 3. Leveling the zombies Up
  Upon clicking the 'level up' button, some gas will be used and the level will be increased of the zombie and clicking on 'show zombies' again, we can clarify the change
## 4. Eye Catching User interface with the buttons and images
  We have added the UI and buttons rather than simple html page
## 5. Feeding the kitty to the zombie



# Features which are in progress, the logic is implemented in the code but we are trying to debug the issues
# Note: It worked twice when we checked but not able to reproduce every time
## 6. Attacking another zombie by giving the address of the other zombie
