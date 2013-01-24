# MusicBrainz.js

## Installation

```html
<script src="js/musicbrainz.min.js"></script>
```

Requires jQuery and CORS

## Usage

### Lookups

Coming soon...

### Search

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
