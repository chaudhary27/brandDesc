# brandDesc

this tool will scrape description from meta tags given a domain_url. text is encoded utf-8. so its possible that not all urls will return some description. also if a website doesn't have meta tags it won't return any description. 


Following dependencies nees to be installd before running

1. pip install pyopenssl ndg-httpsclient pyasn1
2. sudo easy_install requests
3. pip install beautifulsoup4

To run: 
1. enter domain urls in csv file comma separated ex (http://times.com,http://betaboston.com)
2. in your Terminal, cd to the directory you have clones the repo. and type: (python scrape_fb_assets.py ex_15.txt)
3. you can see the brand desc in the txt file.
