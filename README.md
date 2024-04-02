# AND101 Project 6 - CYOAPI Part 2: RecyclerView Edition

Submitted by: Annamarie Cortes

Time spent: 6 hours spent in total

## Summary

MarvelHeroes is an android app that that takes in user query of marvel character displays a scrollable list of the search results of the character with an image, name, and description (if there is one) from the Marvel API

If I had to describe this project in three (3) emojis, they would be: 😄🧠😅

## Application Features

The following REQUIRED features are completed:

- [x] Make an API call to an API of your choice using AsyncHTTPClient
- [x] Implement a RecyclerView to display a list of entries from the API
- [x] Display at least three (3) pieces of data for each RecyclerView item

The following STRETCH features are implemented:

- [x] Add a UI element for the user to interact with API further
- [x] Show a `Toast` or `Snackbar` when an item is clicked
- [ ] Add item dividers with `DividerItemDecoration`

The following EXTRA features are implemented:

- [ ] None

## Video Demo

Here's a video / GIF that demos all of the app's implemented features:

<img src= 'https://i.imgur.com/0gfw1o2.gif' title='Video Demo' width='' alt='Video Demo' />

GIF created with ScreenToGif and Imgur

## Notes

This was a project to demonstrate RecyclerView. Here, RecyclerView was used to implement the scrollable view. I also learned a lot by exploring the Marvel API which needed a private key. 
This was quite a bit of a challenge and this week I was able to figure out how to make this work (I had been trying since last week, gave up, and switched to pokeAPI). 
I had to also add another manifest to clear the traffic for the specific URL. I had to do some research and happened to stumble upon this. I am still unsure why this allowed me to pull
up the images from the Marvel API but I will continue to research and explore as to why.


## License

Copyright 2024 Annamarie Cortes

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
