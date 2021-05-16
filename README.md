# wget-download-full-website
This wget command will download the complete website for you:
```
wget --limit-rate=200k --no-clobber --convert-links --random-wait -r -p -E -e robots=off -U mozilla http://www.yoursite.com/
```
## Instructions
Copy the whole code,\
then change `http://www.yoursite.com` to your website's URL,\
and then paste it inside your terminal & press 'Enter'.

Here is the [video tutorial](https://www.youtube.com/watch?v=pxdIjhTXqok) by [Stacked Up](https://www.youtube.com/channel/UC9sf3XL_6MSabxgF2yKDtmA)
