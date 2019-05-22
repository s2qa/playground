# Search functionality
Tags: search, chrome

The user must be able to search on the search page

* Open the search page

## Successful search
Tags: successful

For an existing product name, the search result will contain the product name

* Search for product "MarketWatch"
* "MarketWatch" should show up in the search results

## Unsuccessful search
Tags: unsuccessful

On an unknown product name search the search results will be empty

* Search for product "nothing"
* The search results will be empty 

## Showing the autosuggestions when put three characters
Tags: autosuggestions

Categories should be listed after the input of three characters, which triggers suggestions for words containing those characters

* Search for "bar"
* The categories with autosuggestions will be shown 

## Hiding the autosuggestions when delete the third character
Tags: autosuggestions

Categories should be hidden after deletion of the third character

* Search for "bar"
* Delete the third character "r"
* The categories will be hidden 

## Closing the search with X button
Tags: close

The X button should close the search

* Pushing button X
* The Search will be closed 

___
This is tear down step

* Close the browser
