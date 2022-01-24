# spam-matrix-and-reddit
Send the same message to multiple matrix rooms / subreddits at the same time

great guide on how to get your reddit api keys here https://www.jcchouinard.com/get-reddit-api-credentials-with-praw/

matrix token can be found (using element web ui) settings -> about -> scroll to bottom and find access token
```
matrix_token = ""
```

you will need to add the reddit keys here:
```
creds = { 
'client_id': "",
"client_secret":"",
"user_agent":"monero_matrix_alerts",
"redirect_uri":"http://localhost:8080",
"refresh_token":"",
}
```
paste in your client id / secret. then run the script. you will be prompted to copy paste you id / secret - and then requested to visit a url. The refresh token will be provided (which you will also copy and paste into the above)
