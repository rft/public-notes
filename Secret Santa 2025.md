#fun #incomplete 

Back in highschool (2018) my friends and I started a tradition of having a secret santa, which led me to this dilemma of how to participate in it without knowing who got who. 

Initially I started with a simple script that would automate sending emails out to each person to let them know who got who, It makes for an interesting little hackathon where I can keep changing or reviewing it every year. 

# A fun little note 
When I first created my script, I created a bijection (a one-to-one) mapping between two different sets, just by shuffling one of the sets and ensuring that a person doesn't get themselves. What I didn't realize at the time was that doing it this way creates derangements (permutation of an elements in a set) that can split the group such that it breaks the chain of gift giving, which we would have to find the next person to start the new chain. 

In a later year I simplified the script so that it just shuffles a single set and has each element give to the next person. It wasn't until someone mentioned at the party "wow what is the chance that we had a perfect loop" that I realized this even had this property and I had just inadvertently fixed it. 


# 2025 Secret Santa - Dating Sim 

![[2025_secret_santa.mp4]]