ROOTRACK

Each post (txt/img/vid) uploaded to the internet will go through Rootrack.

Rootrack will classify each post into 1 of 3 categories – txt, img(+txt) and vid, which will in turn be classified into 1 of 3 categories – appropriate, inappropriate, or content that cannot be determined by Rootrack.

-Humans will have to classify content that cannot be classified by Rootrack

-And once this is done it will be given as input to Rootrack for it to learn.

After classification, each post will be given an ID number and a tracking file will be created for it having the ID number as its name. 

-Tracking file stores details of all occurrences of a post 

All this will be stored in a database.

Each time a post is uploaded onto the internet, the Rootrack checks if the post matches any of its existing contents in the DB.

-If yes, it sends the upload details (IP, time etc) to the tracking file already created.

-If no it creates a new record

When we want to find the origin of a post, we give the post as input to the identifier (tool to find post in Rootrack’s DB) and we can view the tracking file.

Often posts have modifications made by users while they are shared (extra txt, cropped, color change etc.)

-Rootrack will group posts that match more than 70% in the same tracking file and will also list possible modifications

-If Rootrack cannot decide, human intervention will be needed.



