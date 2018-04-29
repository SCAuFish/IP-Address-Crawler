# IP-Address-Crawler
The project to crawl through wikipedia and collect the data of where anonymous editors on specific webpages are.

# Working process
Given a starting wikipedia webpage, the crawler would check all the IP addresses of its anonymous editors and store their
nationality. To keep searching, the crawler would keep visiting all the wikipedia webpages linked by the starting webpage.
Therefore this whole process is recursive.

Recently on my cse class we are talking about stack and that's what I made use of. LOL. Though it's a python set, but I would
store child webpage in the set. This would prevent duplicate webpages being investigated more than one times. The webpage will
be popped from the set when the program wants to visit and crawl over it.
Another visitedSet is used to record all the sets that have been visited.

# Reference
Thanks to Ryan Mitchell's Web Scraping with Python: Collecting Data from Modern Web! This is the book where I learned all 
these techniques from. It's a nice book!
