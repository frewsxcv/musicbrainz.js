# MusicBrainz.js

## Installation

```javascript
<script src="js/musicbrainz.min.js"></script>
```

Requires jQuery and CORS

## Usage

```javascript
MBz.search({
  resource: "artist",
  query: "britney",
  results: function (artists) {
    console.log(artists);
  }
});
```

```javascript
MBz.search({
    resource: "label",
    query: "sony",
    results: function (labels) {
        console.log(labels);
    }
});
```

```javascript
MBz.search({
    resource: "release",
    query: "lift your skinny",
    results: function (releases) {
        console.log(releases);
    }
});
```
