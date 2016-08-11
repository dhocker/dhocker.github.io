---
layout: post
title:  "Respotify - A React Tutorial Immplementation"
date:   2016-08-11 16:00:00 -0600
category: posts
---
© 2016 by Dave Hocker (AtHomeX10@gmail.com)

## Overview
Recently I spent some time going through a React tutorial published by
[Nitin Punjabi](http://patternhatch.com/author/nitin-punjabi/) on his [web site](http://patternhatch.com).
I published my implementation of his React tutorial at [respotify](https://github.com/dhocker/respotify.git).
This tutorial is a three part series with parts one and two being published as of the date of this writing.

The tutorial implementation uses:

- React
- Webpack
- Babel
- axios
- eslint

I've made a few embelishments to the stock tutorial.
- I added highlighting to the track list to clearly indicate when a track is playing.
- Clicking on a track toggles its status. If it is playing it will stop. If it is
stopped it will play. The currently playing tracked is always stopped before another
track is started.

This is a really good tutorial for learning about React and related technologies. In particular,
it helped me learn how to use eslint.

## Useful References
1. [A Primer on the React Ecosystem](http://patternhatch.com/2016/07/06/a-primer-on-the-react-ecosystem-part-1-of-3/)
