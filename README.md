# MusicBrainz.js

Musicbrainz.js is a client-side library for interacting with the [MusicBrainz XML Web Service](http://musicbrainz.org/doc/Development/XML_Web_Service/Version_2). This project is in no way affiliated with the MusicBrainz project nor the MetaBrainz foundation.

## Installation

It's as simple as:

```html
<script src="js/jquery.min.js"></script>
<script src="js/musicbrainz.min.js"></script>
```

As of right now, this library require jQuery. In the future, it will likely no longer be a dependency.

## Usage

### Lookups

Perform a lookup on a MusicBrainz Entity. More information can be found [here](http://musicbrainz.org/doc/Development/XML_Web_Service/Version_2#Lookups).

Coming soon...

### Search

Search for MusicBrainz Entities. More information can be found [here](http://musicbrainz.org/doc/Development/XML_Web_Service/Version_2/Search).

#### Artist search

```javascript
MBz.search({
  resource: "artist",
  query: "britney",
  results: function (artists) {
    console.log(artists);
  }
});
```

#### Label search

```javascript
MBz.search({
    resource: "label",
    query: "sony",
    results: function (labels) {
        console.log(labels);
    }
});
```

#### Release search

```javascript
MBz.search({
    resource: "release",
    query: "lift your skinny",
    results: function (releases) {
        console.log(releases);
    }
});
```
