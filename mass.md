```
cat 1.txt | xargs -i% curl -s -L https://www.% | grep -Eo '(http|https)://(www.)?(facebook.com|twitter.com|linkedin.com|youtube.com|instagram.com|tiktok.com)[a-zA-Z0-9./?=_%:-]*' | anew | httpx -title -status-code -follow-redirects
```

```
cat sghttpx.txt | python3 smuggler/smuggler.py -l smuggletest.txt
```
