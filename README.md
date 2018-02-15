# Example Project

These example files are similar to [pact-js karma/jasmine](https://github.com/pact-foundation/pact-js/tree/master/karma/jasmine) exmaples.

This project is here to expose a potential bug with pact matchers.

The bad pact(s) is located in `pact/`. Notice there are two pacts, but they are identical due to the pact setup in karma
being different from the pact-web constructor

Log file is located at `pact/` but notice in karma.conf.js the default path is located in node_modules, so I need to
go up a few folders to place the log file in the location I would like

### To run
execute `npm test`
