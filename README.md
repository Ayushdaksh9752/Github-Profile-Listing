
# Github Profile Searcher


Search and view users via the Github API.
Requests are cached in session storage to limit the use of the API.



## What is this?

A personal project built with Javascript, HTML and CSS to search users and view their profiles on Github. Nothing serious.
Feel free to open issues for questions/improvements!
```
+ Fork this repo.
+ Do some changes and you may like.
+ Give this repository a star.
```

### API limit

The Github API has a fairly strict limit (hence the indicator of your remaining
requests in the footer). When running the app locally you can export a [personal
access token](https://github.com/blog/1509-personal-api-tokens) and this will be
sent along in any API calls to increase the limit:

```
export USER_SEARCH_OAUTH=<your token>
yarnpkg run start
```


