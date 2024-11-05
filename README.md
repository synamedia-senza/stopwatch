# Stopwatch

This app is a copy of the Unified Player reference implementation, with an additional class called Stopwatch that displays a banner in the top left corner that indicates the amount of time spent in foreground and background modes in the current session. It also shows the ratio of the total time spent in foreground mode. 

See [Profiling Your App](https://developer.synamedia.com/senza/docs/profiling-your-app) and the [Stopwatch](https://developer.synamedia.com/senza/docs/stopwatch) tutorial in the Senza developer documentation.

## Build

```bash
npm ci
npx webpack -w --config webpack.config.js
open index.html
```
