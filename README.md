# Contact-PFP-Change
Script for the iOS app "Scriptable".
You can change all your contact profile pictures with ones from a subreddit of your choosing.
Replace the "subs" variable with a list of subreddits 
Ex. 'var subs = ["subreddit0","subreddit1","subreddit2"]'.

This script will use the reddit api to pull a collection of images that is equivallent to the number of contacts you have. It will then loop through your contacts, crop the image to the proper size, and set it as theirs.
