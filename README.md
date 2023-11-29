## Introduction

- The Ajax Wikipedia Search Project is a JavaScript-based application that utilizes AJAX and the fetch API to interact with the Wikipedia API. The project allows users to search for articles on Wikipedia, display the search results, and navigate to the official Wikipedia site to view the selected article.

- Wikipedia: https://vanilla-js-api-wikipedia.netlify.app

#### API DOCS

- [wiki docs](https://www.mediawiki.org/wiki/API:Main_page)

- Search URL:
  https://en.wikipedia.org/w/api.php?action=query&list=search&srlimit=20&format=json&origin=*&srsearch=searchValue

- list=search - perform a full text search
- srsearch="inputValue" - search for page titles or content matching this value.
- srlimit=20 How many total pages to return.
- format=json json response
- "origin=" fix cors errors
