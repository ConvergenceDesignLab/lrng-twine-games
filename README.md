# Learning Playlist Games for LRNG

## Concept

A series of Twine and vanilla HTML/JS/CSS games & tools built pre-2019 (not by @mikewesthad). I'm archiving them here so that they can be maintained in a versionable way. These were produced for [LRNG](https://www.lrng.org/)'s online learning playlists. A learning playlist is a collection of learning activities around a theme.

## Technical

The game were built with a variety of tools:

- `games/fraud-tips` - vanilla HTML/JS/CSS
- `games/managing-your-account` - vanilla HTML/JS/CSS
- `games/managing-your-account-2018` - vanilla HTML/JS/CSS
- `games/model-employee-tips` - vanilla HTML/JS/CSS
- `games/night-before-interview-2018` - Twine
- `games/tax-forms` - vanilla HTML/JS/CSS
- `games/tax-forms-2018` - vanilla HTML/JS/CSS
- `games/tax-forms-year-round` - vanilla HTML/JS/CSS

### Running

For running each tool, simply open up the tool's folder (e.g. `games/fraud-tips`) in your choosen http server. One way if you have Node installed, open a terminal in the folder and run:

```
npm i -g http-server
http-server -c-1 -o
```

### Deploying

You can copy the contents of any of the `games` folders to a server for deploying, just make sure you are _not_ copy the whole repository folder (which includes .git and the readme).

### Changelog
