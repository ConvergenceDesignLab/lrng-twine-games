# Learning Playlist Games for LRNG

## Concept

A series of web games & tools built pre-2019 (maintained by, but not originally created by @mikewesthad). I'm archiving them here so that they can be maintained in a versionable way. These were produced for [LRNG](https://www.lrng.org/)'s online learning playlists. A learning playlist is a collection of learning activities around a theme.

## Technical

The games were all built with client-side web technologies. Each folder is self-contained and can be hosted as is.

### Running

For running each tool, simply open up the tool's folder (e.g. `games/fraud-tips`) in your choosen http server. One way if you have Node installed, open a terminal in the folder and run:

```
npm i -g http-server
http-server -c-1 -o
```

### Deploying

You can copy the contents of any of the `games` folders to a server for deploying, just make sure you are _not_ copy the whole repository folder (which includes .git and the readme).

### Changelog

03/11/2019:

- Moved tax tools to [ConvergenceDesignLab/tax-resources](https://github.com/ConvergenceDesignLab/tax-resources)

01/18/2019:

- Restructure so that each game is modular and does NOT depend on a `../globals` folder, @mikewesthad
- Remove unused clipboard dependency, @mikewesthad
