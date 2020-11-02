# AITA

This is a small project where we analyze some posts from the "Am I the asshole" subreddit.
This is a forum dedicated to real-life conundrums, when the poster describes a situation in their lives and how the acted, and asks if they were "right" ("Am I the asshole?") in pursuing that course of action.
The users react by giving a morality verdict - "You're the asshole" or "Not the asshole".

We train a NLP model to predict the moralidy verdict based on the text of the original post.
It does not fare terribly well, because most of these dilemmas are not particularly clear-cut.

The main interest of this project was to get practice and train a Bert model from the transformer library (by Huggingface).
