# Game Design Document

## Introduction

### Game summary pitch

BD-Scape is a story/puzzle game where you can influence the book you are reading by picking objects and using them inside the book.

### Inspiration

#### Myst

Myst makes you solve puzzle by interacting with your environment. You pick objects and gather clues that will help you advance in other parts of the game.

#### The Stanley Parable

The Stanley Parable has multiple endings that depend on the actions you decide to perform.

#### Escape Books

Escape books give the player a way to get involved in a story by making actions.

#### Groundhog Day

Similar to Rogue-like/lite games, the game (book) restarts from the beginning every time. However, the information gathered by the player stays and new actions can be performed.


### Player Experience

The player will play as if he/she was reading a book. The player can only advance in the book their, actions are definitive and will advance them towards a certain ending. In each playthrough the player will gather new information that will help them find new endings, finding their way towards the "true ending".

### Platform

The game is developed to be released on itch.io

### Development Software

- Godot Engine version >= 4.4

### Genre

Puzzle, Story, Singleplayer

### Target Audience

The game is aimed at casual gamers that focus more on the story and puzzle solving part of the games.


## Concept

### Gameplay Overview

The player is reading a comic book. As the book progresses, they can grab objects from the comic and use these objects elsewhere in the comic.
The player can only advance in the comic book. When the player uses an object to discover a new place, the following pages are changed, leading to another ending.

### Primary Mechanics

#### Extract and Interact

The player can grab certain objects from the book. They can also interact with some objects, sometimes requiring to have an object or to solve a puzzle.

#### One-Way Reading

The book must be read in one go. Once the last page is read, the player returns to the beginning.

### Secondary mecanics

#### Information Gathering

The objects you can interact with are initially mixed with the rest of the image. As you progress, you unlock hints that will help you see the objects you can interact with. These hints are preserved even after each restart of the book.

#### Pages distinction

The page are separated between interaction and movement pages.
- The interaction pages contain information to progress further into the game and objects to grab
- The movement pages contain decisions that will change the outcome of the book



## Art

TODO



## Audio

### Ambiance

Audio sounds are played corresponding to the current page opened. It improves the player's involvment in the scene by playing associated sounds (for example keyboards clicks in an office space, or elevator music inside an elevator).

### SFX

Interactions with the environment make specific sounds



## Game Experience

The game is designed as a point-and-click. All the actions are performed using the mouse. The objects must be clicked. They can be highlighted when hovered (or when hints are found). To change page the side of the page can be clicked, or in the case of a manhwa it is scrolled.


## Development Timeline

### POC

- [ ] One story line with few branches
- [ ] Basic page change
- [ ] Basic art for the pages
- [ ] Grab objects
- [ ] Basic Objects UI

### MVP

- [ ] Better story line
- [ ] Book page change (3D-ish)
- [ ] Configuration file to define scenes
- [ ] Save file
- [ ] Ambiance sounds
- [ ] Objects sounds
- [ ] Better object UI


### Beyond

- [ ] Even better story
- [ ] Even better art
- [ ] 