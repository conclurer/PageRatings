# Page Ratings

This module for [ProcessWire](http://processwire.com) provides a simple API for storing user ratings for pages.

### Methods for $page

```php
$page->votes	// => 5
```

Returns the amount of votes for this page.

```php
$page->averageRating	// => 4.3
```

Returns the average of all ratings for this page.

```php
$page->currentRating	// => 4
```

Returns the current user's rating for this page.

```php
$page->hasVoted		// => true
```

Returns `true` if the current user has rated this page.

```php
$page->resetRatings()
```

Deletes all ratings for this page.

```php
$page->addRating(4)
```

Adds the current user's rating to this page. The rating must be between 1 and 5.

### Translation

The module includes a German translation. Please add the language file to your German language in ProcessWire.