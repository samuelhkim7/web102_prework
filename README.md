# WEB102 Prework - Sea Monster Crowdfunding

Submitted by: Samuel Kim

Sea Monster Crowdfunding is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: 3 hours spent in total

## Required Features

The following **required** functionality is completed:

* [X] The introduction section explains the background of the company and how many games remain unfunded.
* [X] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [X] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [X] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [X] Functioning navbar that brings user to "Our Games" section

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='https://i.imgur.com/KWBZ12P.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />
GIF created with ...  
[Kap](https://getkap.co/) for macOS

## Notes

While building this application, I encountered several learning opportunities and challenges with the JavaScript aspects. Key areas included understanding the logic for `deleteChildElements`, particularly how to remove all existing children from a parent element before displaying a new, filtered list of games. Additionally, getting comfortable with the concise syntax of arrow functions, especially when they are used as callbacks in array methods (like `game => game.pledged < game.goal`), was a new concept. Finally, using the ternary operator (for instance, `unfundedCount === 1 ? 'game' : 'games'`) for conditional string creation offered a neat shorthand compared to traditional `if-else` statements, though it was less immediately readable at first.

Overall, these JavaScript features were powerful tools for building the dynamic aspects of the crowdfunding page, and working through these challenges was a valuable learning experience.

## License

    Copyright 2025 Samuel Kim

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
