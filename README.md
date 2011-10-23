#SmartLogger
A JavaScript logging utility that wraps around the _web_ _console_ feature, provided by modern browsers, to ensure that client-side debugging works irrespective of whether a feature is supported in a browser or not.

## Features

* Wraps calls to _console_ in exception handlers so you wouldn't have to bother about browsers lacking consoles
* Has different logging levels, like DEBUG, LOG, INFO, WARN, etc

## Usage
```javascript
var logger = com.cre4nslab.SmartLogger;
  
logger.setLoggingLevel(logger.INFO);
logger.debug("This won't show since DEBUG is lower than INFO");
```

