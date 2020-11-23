# youtube Sentiment Analysis


## setup google cloud
  1. Go to [Google Cloud Console](https://console.cloud.google.com) and create a new project. 
  2. Enable the YouTube Data API v3.
  3. Create credentials (OAuth client ID, Application Type: Other/Desktop) and download them to `client_secrets.json`.

large part of main.py is the work of 

## running script
`python3 main.py --videoid=gtC-UPk3u8I` , 'gtC-UPk3u8I' is id in this case.

## dataset
after running the py script, you should be able to see your own compound.csv

## running jupyter
final step, now you should be able to see **your own video** stats.

this work is inspired from [John Fish senticomment](https://github.com/johnafish/senticomment)
