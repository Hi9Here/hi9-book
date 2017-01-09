[Home](../hi9-home-page.md)

# Remit for Hi9

Centre of UX and UI is the **Card**

## Main Section

## Card States

### Default
A small card in portrait mode with

* Title
* Sub Title
* Icon

Links in each corner with

* Favorite
* Alerts
* Share
* Settings
  * Delete
  * Edit

### Expanded
  `expandable true`

  More information such as
  * Content
  * Survey Questions
  * API from a Service

## Card Types

* Single Card
  * Website Link
    * `expandable false`

* Content Card
  * Expandable to Summary Content and Header Image. Pulls in RSS
    * `expandable true`

* Native Card
  * Cards designed by Us such as Facebook and Gmail with APIs
  * Event Card
  * Voting Card
  * Survey Card
    * `expandable true`

* Deck Card
  * Card that holds the theme of the deck and appears as a deck of cards image. This holds the information of what the others cards are and it's own tag that is used under a category
  * Expands showing the cards in the deck
  * You can create decks by putting one card on top of another
    * `expandable is true`
