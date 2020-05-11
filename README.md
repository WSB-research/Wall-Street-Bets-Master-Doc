

# Wall-Street-Bets-Master-Doc
Hey, guys. Welcome to the GitHub page. We'll be splitting it up into a few different sections, depending on area of research. 

The workflow of this project is largely going to be dictated by its main purpose, which is identifying vulnerable assets, in particular, corporate debt. There are a few subtopics that we might explore that lie a bit outside the scope of that, but by and large, the thrust is debt. Here's a rough outline of the game plan, broken down into steps:

1. FA team will identify at-risk market demographics, including foreign banks and distressed debt generally.
2. They'll be crosschecked by other FA members until a consensus is reached on risk levels; justifications for each in a writeup would be great
3. Tickers will then be passed on to the TA/data guys, who can set up a bunch of indicators and alerts and generally work their computer magic to best predict the window in which these will fail; graphs and math are appreciated

We now have a list of vulnerable target securities that we're going to work on exploiting: CMBS; Shadow bank bonds (like Quicken); Oil bonds; Tech bonds

We need to begin identifying BTOs (if possible (BTOs are just CLO/CDOs, because of course they are)) that target these assets. They're going to fail. Stay tuned, I'm just writing this down so I don't forget it.


I'd like regular check-ins with progress. We have mandatory weekly meetings at 5pm EST.

scarvesandsuspenders is your TA team lead; ParadiXe is your FA team lead; Jellyra is your macro team lead. louch aka The Dude In A Suit is master-of-all-trades, jack-of-none. He's kind of like a magic 8-ball, except he's always right. Be nice to him and you might be rewarded.
Chuckles is the dev lead, does not code much, but he will point you in the right direction. And last but not least, it's joesocktwo aka Gitmo Joe, he is a dipshit and some kind of lead.

If you have any concerns, comments, questions, or suggestions, please feel free to hit me up on discord or bring them to the attention of your team lead.

I really appreciate your time and enthusiasm, guys. I'm stunned that I was met with such a flood of excited talent; you guys are experts and actual powerhouses in each of your fields. It's impressive, and I'm really happy to be a part of this. I'm going to do my best here to keep morale up and attention focused; the death of this project will be waning enthusiasm. I don't want to act like a boss or a manager, but I do want to keep everyone working towards this goal. Expect to put at least an hour or two of work into this every week to keep the wheels turning. As long as everything keeps flowing, I'll be here nonstop to keep things moving and handle anything that needs handling. I don't know how this is going to turn out, but between the lot of you, there's an incredible pool of potential to tap into and use to our advantage. Let's make some tendies, guys.

## Contributing to the Github Repository

1. Create a branch by selecting the branch dropdown, typing a name, and click Create. 
2. Navigate to the folder or file you want to change. 
3. Upload files or edit the file you want, and at the bottom, commit it directly to the branch you just created. 
4. Navigate back to the home page of the repository
5. You should see the option to create a New Pull Request. Click that, and submit a Pull Request from your new branch into master. 
6. Your changes will be approved and merged in shortly. 

## First steps
1. Register in https://git.wsbresearchllc.com/ and dm Chuckles to invite you to the group
2. Register in https://tasks.wsbresearchllc.com/ and dm FA lead what is going on there

## Current tasks for developers
1) Pulls all the NPORTs on the SEC website (currently completed) and will visualize it for the end user by sector, financials, etc (this portion not completed and is currently handled by utopian).
2) Pull 10ks and 10qs, do the same visualization thing + financials ranked via our own and the users parameters. Sort of like a very extensive screener. We hope to add machine learning here to go through sector by sector, category by category & see if it could detect anomalies relative to other companies (not complete yet)
3) An option screener that with the help of math & hopefully ML/historical data will detect statistical anamolies, mispriced options and significantly deviant purchases on the fly. (work in progress).
