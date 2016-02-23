Remit for Hi9
=============

Centre of UX and UI is the card

### Card States

#### Default
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


### Card Types

* Single Card
  * Website Link
    * `expandable is false`

* Content Card
  * Expandable to Summary Content and Header Image. Pulls in RSS
    * `expandable is true`

* Native Card
  * Cards designed by Us such as Facebook and Gmail with APIs
    * `expandable is true`

* Deck Card
  * Card that holds the theme of the deck and appears as a deck of cards image. This holds the information of what the others cards are and it's own tag that is used under a category
  * Expands showing the cards in the deck
    * `expandable is true`

#### Expanded
`if true`

More information such as
* Content
* Survey
* API from a Service



You can create decks by putting one on another
