# Infinity

Infinity is your journey into a universe born of AI, where you can explore, interact and chat with characters; the only limit is your imagination.

![alt banner](https://raw.githubusercontent.com/lrusso/Infinity/refs/heads/main/README.jpg)

## How to create your universe

The universe is defined in the `strings.js` file at [line 8](https://github.com/lrusso/Infinity/blob/main/src/public/strings.js#L8-L44) and the welcome text at [line 45](https://github.com/lrusso/Infinity/blob/main/src/public/strings.js#L45).

## God mode in your universe

As you explore your universe and interact with the characters, anything you write in parentheses will happen. For example:

- (I smile)
- (I go to the office)
- (A new person comes to the office)
- (Willy enters the house and starts barking)

## How to run the server

- Run `npm install`
- Run `npm run download:q8` or `npm run download:q3` (for systems with limited RAM)
- Run `npm run start`
- Browse to `http://localhost`

## How to run the server using a different port

- Run `npm run start 8080`
- Browse to `http://localhost:8080`

## How to run the server in the background

- Run `npm install -g forever`
- Run `npm run forever`
- Browse to `http://localhost`
- To stop the server, run `npm run stop`

## Forcing the light and dark modes

- Browse to `http://localhost/?lightmode`
- Browse to `http://localhost/?darkmode`

## Disclaimer

You are legally responsible for any damage that you could cause with this software.
