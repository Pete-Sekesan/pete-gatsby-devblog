---
title: Junior Web Dev Hackathon Conclusion
date: 2021-08-09
description: # Add post description (optional)
img: ./frustrated-developer.png # (optional)
---

# Well...it's done.

And by done now, it was done last week. My grand plan to update daily failed miserably. There was just too many things going on coupled with the intensity of finishing the project.

## So how did we do?

Let me preface this by saying, I am extremely proud of the work my teammate and I put into this. Did we get a fully functional application running 100%?

_No._

But we did get about 80% of the way there over the course of 5 days. We decided to go big and that is lesson number 1 I have learned from this experience.

### Keep it simple!

We had grand plans of figuring out the logic for Blackjack, learning Sockets to implement multiplayer and live chat while also trying to learn Material UI to save time in on laying out the UI.

I know, this all sounds insane to take on. I am sure (maybe, possibly?) that this would be crazy for even a more experienced developer. Certainly not something two junior level devs should be taking on. But we wanted to take this as a learning opportunity as well. So what did we accomplish you may ask? BTW, we later shifted to making this a game of High Card Draw with individual hands available to wager.

- Implemented a backend using Node.js, Express.js and PostgreSQL to allow users to sign in and upload a profile image using Cloudinary. We used JSON Web Tokens to authorize each user.

- Figured out how to use the Cards API to pull in card data and images. We then used this to assign each card a value.

- Since we abandoned multiplayer, we needed a reason to have a logged in user in the first place. We used this to pivot to displaying on the signed in users dashboard a leaderboard of all participants sorted by how much "money" that had made playing.

- Got the logic working to bet a hand and have that update the users Wallet.

We had so many of the pieces there but just ran out of time. Both of us were doing this on our free time while also both having children under 3 running around the house. We plan to finish this application regardless of the due date having past. We think it can be an excellent way to show off many of the skills we learned in our boot camp and what we have learned since.

We will be sure to start smaller next time and add features as time permits. Overall though, I had a blast working on it.
