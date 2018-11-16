# EMOJI MARKDOWN SEARCH

[Click here to access the world of emojis](https://obscure-shore-44689.herokuapp.com/)

Ever tried to use a specific emoji but forgotten what the markdown was for it? Never fear,emoji markdown search is here!
![](https://i.imgur.com/PHxtUej.png)

We were hoping to implement a super smart algorithm that would present emoji based not only on name but also on sentiment(this didn't happen)
The big challenge this week was tackling the autocomplete functionality which ended up taking more time than we planned so we didn't have time to add other functionality that we had planned. After code review, we modularised our code, added some responsive styling and enhanced the search/autocomplete functionality by adding emojis to the autocomplete to help you identify what you are looking for. We also added a delay to the API calls as the autocomplete would change too frantically and was a distraction.

## Design

Because of time constraints we decided to go with a minimalist design and use bright colours. For this weeks design challenge we used a modal (technically both a space-saving container and an informational component). We fulfilled many of the autocomplete best practices (except magnifying glass icon, highlighting the differences, and categorising):

* Display the search field prominently
* Provide a search button for the search box (don’t presume the user will press enter)
* Avoid scrollbars and keep the list manageable (limit the number of items in a list)
* Match user hover expectations (i.e. change colour on hover)

![](https://i.imgur.com/7AkxlcE.png)

## Stretch Goals

* Searching by aliases as well as by 'proper' names
* Creating a fallback drop-down list for Safari as datalists don't work
