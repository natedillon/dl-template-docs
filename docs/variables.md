# Variables

Available variables to use within a Delicious Library site template.

## Library Information

### $addressBookImage48

Adds your profile image from your OS X Address Book app. This outputs as a relative path to an image file that is created during the publish process.

Example output:

    covers/E572AB8B-F9C0-4265-9767-F4B10CB29847.png

### $fullName

Full name of the site.

### $totalItems

Total number of items in the library. This will also add the word "Items" to the end of the output.

Example output:

    856 Items

### $publishDate

Date the site was last published.

Example output:

    Dec 2, 2013

## Navigation

### $shelfNavigationPopup

Shelf navigation, outputted as a `<select>` list with class "shelf_selection".

Example output:

    <select class="shelf_selection" onchange="location.href = this.options[this.selectedIndex].value;">
        <option value="index.html" selected="selected">Books</option>
        <option value="games.html">Games</option>
        <option value="movies.html">Movies</option>
    </select>

### $pageNavigation

Example output:

    <span class="arrow left">&nbsp;&nbsp;&nbsp;</span> 
    <span class="pages">
        <span class="page">1</span> <a class="page" href="movies-2.html">2</a> <a class="page" href="movies-3.html">3</a>
    </span> 
    <a class="arrow right" href="moviesdvd-2.html">&nbsp;&nbsp;&nbsp;</a>

## Media

### $coverImage128

Example output:

    <img class="coverimage" src="covers/9EEB7BDC-9D15-4358-8390-0E7C2888C318-128.png" width="91" height="128">

### $amazonURL

Example output:

    http://www.amazon.com/dp/B001UV4XUG?SubscriptionId=1XKMQ76GH235KSFB1M02&amp;tag=deliciousmons-20&amp;linkCode=xm2

### $title

The title of the media.

Example output:

    (500) Days of Summer

### $creatorsCompositeString

Media creator. For example, the director of a movie or the publisher of a game.

Example output:

    Stanley Kubrick

### $purchaseDate

The purchase date of the media.

Example output:

    Apr 7, 2011

### $librarySearchString

Example output:

    Manhattan, Kansas zipflap congrotus delicious library Dillon, Nate
