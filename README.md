# Shell-data-processing
## Powershell commands to create a project
- To create new folder `mkdir shell-data-processing`
- To create new README file in the folder `ni README.md`
- To create new .gitignore file in the folder `ni .gitignore`
- to list the files in folder `ls`
## Curl
- I used curl to retervie the text from a page the commands are as follows
- To retervie a page text `curl https://en.wikipedia.org/wiki/Node.js`
- To return page text and output of a file `curl "https://en.wikipedia.org/wiki/Node.js" -O data.txt`
## Data processing
- To Transform each space ' ' into a return character '\12' (aka ASCII line feed) `tr ' ' '\12' < data.txt`
- To sort the data alphabetically,bumber or month we use Pipe the output to sort (send the results of one command as input into another command) `tr ' ' '\12' < data.txt | sort`
- To count each entry we use The sorted output to uniq -c to count `tr ' ' '\12' < data.txt | sort | Uniq -c`
- Reduced output to sort with -nr flag `tr ' ' '\12' < data.txt | sort | uniq -c | sort -nr`
- To Redirect the output to result.txt `tr ' ' '\12' < data.txt | sort | uniq -c | sort -nr > result.txt`



