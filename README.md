# pruitt-emails
Emails released by CMD about Scott Pruitt

### Goals:

* Who - who are the people sending these messages? Who is receiving them? Who do they work for?
    * Who are the most common senders or receivers?
    * Social network analysis. Look for measures of centrality.
* What - what words/topics are more common when sent from the AG's office to each recipient? 
* Do the same sender/recipient analysis, but by sending receiving organization. 

### Steps

* Parse the emails into a data frame, with fields for from, to, when, subject, and message body. Include bate stamps for reference. 
    * This is in [Email Splits](Email%20Splits.ipynb)
* (Nice to have) - each message has a link to an HTML page for the original email with its formatting
