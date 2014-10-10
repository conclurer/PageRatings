# Page Ratings

This module for provides a simple API for storing user ratings for pages.

### Ratings API

You can access the Ratings API via the `$page->ratings` property.

This includes the following methods:

- `$page->ratings->count` the amount of votes on this page
- `$page->ratings->average` the average of all votes on this page
- `$page->ratings->current` the current user's rating on this page, `0` if the user hasn't rated this page yet
- `$page->ratings->hasVoted` returns `true` if the current user has already voted on this page
- `$page->ratings->reset()` will reset all ratings
- `$page->ratings->add($rating)` will add an rating from the current user on this page. The rating must be an integer between 1 and 5.


### Translation

The module includes a German translation. Please add the language file to your German language in ProcessWire.