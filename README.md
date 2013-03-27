songDownload
============

A command line tool to extract and download mp3 of a song that exists on a youtube efficiently and with the least bandwidth usage.

When one is inside a low speed network or a data usage limited network then it is tough to ope youtube site and get the url of best one and then open a youtube video to mp3 conversion site to download an mp3, but instead with this  tool you supply all the search keywords as arguments.
The tool gets the HTML page corresponding to the youtube search and can also suggests/shows the spell corrections suggested by youtube instead when the search returned no results. It will quickly go through some factors that will classify a result better than other's like OFFICIAL tag, number of views e.t.c. It will re-score each result and returns with the best result. Information about the best results are displayed and also it tries to fetch and show the image with fbi image viewer.[fbi because I hate it when a window pops up.] If the results that it is showing are satisfactory to your standards then you can continue or abort the process here.

You can also specify --video option which will try to fetch the video with youtube-dl [see the list of dependent software and packages] instead of mp3, by default it will fetch mp3.

Scoring of the results is tolerant to spell mistakes to some extent unless or otherwise the words are terribly misspelled, As the approximate measure of distance is used rather than brute force matching and some amount of distance between two strings is tolerated for misspells.

This tool uses youtube-mp3.org to convert between video and mp3.



