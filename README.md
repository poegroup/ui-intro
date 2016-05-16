# ui-intro
introduction to poe-ui

## Initialize a poe-ui app

* install (poe-cli)[https://github.com/poegroup/poe-cli]
* `mkdir ui-intro && cd ui-intro`
* `poe create ui`
* follow prompts (you can set the api_url to any poe-api url, for demo use `http://mz-class-roll.herokuapp.com/`)
* done

## start new initialized app
* `npm i`
* `make`
* `open http://localhost:5000`

## Jade
We use (React.js)[http://facebook.github.io/react], but we write in the (jade)[http://jade-lang.com] syntax, so you can leverage all of the react component life cycle, but you get to write in clean syntax provided by Jade.

## ESS
We use EcmascriptStyleSheets (ESS) for our css pre-processor. It's super powerful and does lots of fancy things for us, feel free to read the code (here)[https://github.com/css-utils]

## License
MIT