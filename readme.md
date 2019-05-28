# Agile Trello

A Chrome extension which provides all the Scrum/Kanban tools

## Get Started

[Get started tutorial](https://developer.chrome.com/extensions/getstarted), first step shows how to setup the developer version to test it out.

- Main file is `agile-trello.js`

## Dynamic importing

- Add new file to manifest.json in `web_accessible_resources`
- Import using `import { nameOfFunc } from './random-file.js'` **important of end with file extension**

## Features:

> Add more things to the list

- [x] Total card count per column (Richard)
- [x] Total story points per column (Richard)
- [x] Implement dynamic importing of js modules (Richard)
- [x] Implement an observer for when cards move (Richard)
- [ ] Display points on card (Toby) <- still needs to hide the points in the title.
- [ ] Logo/icon for extension (Laura)
- [ ] List of buttons story points (_Fib numbers_) in open card view to add
- [ ] Story limit per column
- [ ] Show card id (Richard)
- [ ] Age of card from when it was moved/created (Steffi)
- [ ] When a story point has changed on a card update all the totals (column and card points)
- [ ] When changing the board the Agile trello stats are not visible/created
