# Textual

# OLD EUPHORIA README
[<img src="https://travis-ci.org/nicolasmccurdy/euphoria.png?branch=master"
alt="Build Status" />](https://travis-ci.org/nicolasmccurdy/euphoria) [<img
src="https://gemnasium.com/nicolasmccurdy/euphoria.png" alt="Dependency
Status" />](https://gemnasium.com/nicolasmccurdy/euphoria) [<img
src="https://codeclimate.com/github/thenickperson/euphoria.png"
/>](https://codeclimate.com/github/thenickperson/euphoria)

Euphoria is a site dedicated to creating, editing, and playing text adventures
collaboratively. Euphoria is not a MUD, but multiplayer world exploration and
editing is planned. Euphoria is sort of a game, but it is more of a game
community.

## Status
In early development. Contributions, ideas, and questions are welcome. Feel
free to fork this and/or submit issues!

## Goals
- classic text adventure gameplay with an easy to use editor
- collaborative editing and exploration
- Heroku compatible
- mobile support
- modern game features such as achievements, user profiles, and chat

## Inspired by
- classic interactive fiction games, especially [Zork](http://en.wikipedia.org/wiki/Zork)
- [Glitch](http://www.glitchthegame.com/)
- [Parchment](https://code.google.com/p/parchment/)

## Requirements
- Ruby 2.0
- node.js (for assets)
- sqlite for development and testing
- postgresql for production

## Setup
1. Clone the repository.
2. `bundle`
3. `rake db:setup`
4. `rails server -d`
5. Visit `localhost:3000`.
