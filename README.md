# Mr.Meeseeks, a Search Engine


Have you ever had to find stuff on the internet, but only wanted to look through certain websites? Of course you have. Here’s one way to solve that problem, in Python 2.
Jokes...


Problem Description (from http://www.math.ucla.edu/~rombach/PIC16_project2.pdf):

This engine uses a list of urls as its “internet"

•The engine creates a network based on links between the pages in the source code of any page

•The engine understands the meaning of quotation marks

•The engine does pagerank on the sub-network of the pages that contain the search term from the user, and then lists the first few, together with a small snippet of the text on the page. This should be a snippet that contains the highest concentration of the search term words.

TODO: ritght now it automatically corrects the typo
•Your engine recognizes typos, and says “Did you mean...?” The suggestion it gives will be the word in its dictionary (for example: http://mieliestronk.com/corncob_lowercase.txt), that is closest to the search term.
