### Original Features

- : the time (in seconds) when the comment was posted 
- : number of upvotes on the comment
- : id of the specific subreddit
- : id of the particular comment thread
- : name of the comment
- : 1 if the score of the comment was hidden; 0 else
- : CSS class for the comment flair
- : flair text for the comment
- uid=501(areevesman) gid=20(staff) groups=20(staff),701(com.apple.sharepoint.group.1),12(everyone),61(localaccounts),79(_appserverusr),80(admin),81(_appserveradm),98(_lpadmin),33(_appstore),100(_lpoperator),204(_developer),250(_analyticsusers),395(com.apple.access_ftp),398(com.apple.access_screensharing),399(com.apple.access_ssh): id of the comment (basically the same as comment name)
- : reason a comment was removed (either  or )
- : the number of gilded tags (~ premium likes) on the comment 
- : number of downvotes on the comment
- : if the thread was archived (no new comments, no new likes) 
- : author's reddit username
- : number of upvotes
- : The time (in seconds) when the comment was pulled to create the dataset. 
- : the comment itself
- : the type of user on the page. Either , , or . 
- : whether (1) or not (0) the comment has been edited
- : a Boolean indicating whether (1) or not (0) a comment is controversial -- i.e., popular comments that are getting closely the same amount of upvotes as downvotes. 
- : the id of the comment that this comment was replying to.  if the comment is not a reply


### Benchmark v1 Features

- : time comment was posted
- : time since first comment on thread
- : Whether or not there is flair text for the comment
- : Whether or not there is a CSS class for the comment flair
- : depth of comment in thread
- : score of parent comment (NaN if comment doesn't have a parent)
- : time since parent comment was posted
- : subreddits linked in the comment
- : urls linked in the comment
- : number of subreddits mentioned in the comment
- : number of urls linked in the comment
- : number of instances of I
- : whether or not the comment has been edited
- : whether or not comment quotes another
- : number of quotes in the comment
- : negative sentiment score
- : neutral sentiment score
- : positive sentiment score
- : compound sentiment score
- : Number of words in the comment


### Benchmark v2 Features

Scraped
- : url of thread comment is on
- : number of comments on thread comment is on
- : Whether or not the thread has been marked as NSFW
- : upvotes of on thread comment is on
- : selftext of thread if it exists
- : title of thread
- : The percentage of upvotes from all votes on the thread
- : number of upvotes on thread

Engineered from scraped data
- : time thread was created
- : time since the thread was created
- : whether or the comment is a parent
- : whether or not thread comment is on had selftext
- : consine similarity between comment and its parent comment's embeddings
- : consine similarity between comment and its thread's title's embeddings
