# flairs
User flairs on r/soccer

<br />

**IN PROGRESS**

<br />

[Introduction](#introduction)

[Questions to answer](#questions-to-answer)

[Challenges](#challenges)


### Introduction
I am doing some exploratory analysis and data visualization of user flairs on the subreddit, r/soccer. Flairs are little badges a user 
can have beside their username to show which team they support. 

![Flairs on r/soccer](https://i.redd.it/h8x41bzbk2641.png)

Flairs are a way of communicating to other Reddit users where you stand, giving context to your comment. It removes the need for each 
individual to type "_I support x team, btw_" or "_As a x fan, ..._" 

Using [PRAW](https://praw.readthedocs.io/en/latest/), The Python Reddit API Wrapper, I extracted information about posts and comments 
and answered questions I was curious about. 

### Questions to answer

+ General exploration

    + Which flairs get the most upvotes? 
    + Which flairs are the most plentiful? 
    
+ Hypothesis testing questions
    + Is there a cyclic pattern to flair frequency? Can we see teams grow and lose popularity? 
    + Is there a 'siloing' effect where only similar users comment on a post? 


### Challenges
+ Producing useful data visualizations and good writing, instead of just jupyter notebooks
+ Using SQL to manage database
