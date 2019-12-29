# flairs
User flairs on r/soccer

<br />

**IN PROGRESS**

<br />

[Introduction](#introduction)

[Questions to answer](#questions-to-answer)
    
   + [Does everyone have a flair?](#does-everyone-have-a-flair)

[Challenges](#challenges)


### Introduction
I am doing some exploratory analysis and data visualization of user flairs on the subreddit, r/soccer. Flairs are little badges a user 
can have beside their username to show which team they support. 

![Flairs on r/soccer](https://i.redd.it/h8x41bzbk2641.png)

Flairs are a way of communicating to other Reddit users where you stand, giving context to your comment. It removes the need for each 
individual to type "_I support x team, btw_" or "_As a x fan, ..._" 

Using [PRAW](https://praw.readthedocs.io/en/latest/), The Python Reddit API Wrapper, I extracted information about posts and comments 
and answered questions I was curious about. 

[1% rule of internet culture](https://en.wikipedia.org/wiki/1%25_rule_(Internet_culture)): Only about 1 percent of users on a website create new content. For example, there are 1.8 million users subscribed to r/soccer, but an average post only has 500 upvotes and top posts of the month have 35000 upvotes. The results of this analysis apply only to commenters on the subreddit. 

### Questions to answer

+ General exploration

    + #### Does everyone have a flair? 
        I sampled a random 5 percent of the top 5000 posts for the month on r/soccer. For each post, I recorded all the comments and their users flairs and found that 28 percent of users have not chosen a flair. That is, about 7 out of 10 individuals have chosen a team or country to represent them. The data is available  in a csv file [here](https://github.com/ayoola-babatunde/flairs/blob/master/printout.csv). 
    + Which flairs get the most upvotes? 
    + Which flairs are the most plentiful? 
    
+ Hypothesis testing questions
    + Is there a cyclic pattern to flair frequency? Can we see teams grow and lose popularity? 
    + Is there a 'siloing' effect where only similar users comment on a post? 


### Challenges
+ Producing useful data visualizations and good writing, instead of just jupyter notebooks
+ Using SQL to manage database
