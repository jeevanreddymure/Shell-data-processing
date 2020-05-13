# Shell-data-processing
## Curl
- I used curl to retervie the text from a page the commands are as follows
- To retervie a page text [[[curl "https://en.wikipedia.org/wiki/Node.js"]]]
- To return page text and output of a file [[[curl "https://en.wikipedia.org/wiki/Node.js" -O data.txt]]]
## Data processing
- To Transform each space ' ' into a return character '\12' (aka ASCII line feed) [[[tr ' ' '\12' < data.txt]]]
- 


