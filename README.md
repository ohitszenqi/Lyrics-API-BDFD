# Getting started
*Lyrics API is an api that send lyrics on your made-with-BDFD Bot*

# Usage
```
https://lyrics-search-query-api.seancainglit.repl.co/?song=title of your song here.
```
### Example:

```
$nomention
$httpGet[https://lyrics-search-query-api.seancainglit.repl.co/?song=$replaceText[$message; ;+;-1]]
$title[$httpResult[views]]
$description[
**Author:** $httpResult[author]
**Lyrics:** 
$httpResult[lyrics]
]
$color[37e4ff]
$botTyping
```
