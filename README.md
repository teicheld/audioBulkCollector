# audioSearcher

It searches, filters, sorts and collects youtube-playlists for you. 
Just hand them over to youtube-dl and fill your storage for offline times.

If you want to see a sample output, there is a file called sample_output.txt.

## usage

./list2audioBulk.sh searchTermList [whitelist]
whitelist = removes all playlists whitout one of the words. Newline-seperated
if you dont provide a whitelist the searchTermList becomes also the whitelist.

### what does it do in detail?

it searches youtube for playlists which include also a keyword on the whitelist.
