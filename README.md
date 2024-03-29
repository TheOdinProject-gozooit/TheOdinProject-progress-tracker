# TheOdinProject Progress Tracker

## Introduction

### About me

With a background in computer science, I have been working in this field for several years, especially in the user support, systems and networks areas. During my studies, I had the chance to be introduced to development. Unfortunately, it didn't catch my interest at first, but the more I looked into it, the more I've been excited about it.

So I first started with the basics in Python, building some small tools for my personnal use. Then I (re)discovered web development (that I used to hate during my sudies) and felt in love with it. This is why I decided to fully immerse myself in learning web development. I came across The Odin Project which contains exactly what I was looking for: a way to learn on my own and to progress step by step in this field.

### About this repo

This repository is a homepage about my progress on The Odin Project. It contains links to all the projects I have done in relation to it.

## Ruby <img src="https://progress-bar.dev/47?title=Progress&width=180&color=333333" align="right">

### [Caesar Cypher](https://github.com/TheOdinProject-gozooit/caesar-cipher)

Implement a caesar cipher that takes in a string and the shift factor and then outputs the modified string:
```ruby
> caesar_cipher("What a string!", 5)
=> "Bmfy f xywnsl!"
```

### [Sub Strings](https://github.com/TheOdinProject-gozooit/sub-strings)

Implement a method `#substrings` that takes a word as the first argument and then an array of valid substrings (your dictionary) as the second argument. It should return a hash listing each substring (case insensitive) that was found in the original string and how many times it was found.

```ruby
> dictionary = ["below","down","go","going","horn","how","howdy","it","i","low","own","part","partner","sit"]
=> ["below","down","go","going","horn","how","howdy","it","i","low","own","part","partner","sit"]
> substrings("below", dictionary)
=> { "below" => 1, "low" => 1 }
> substrings("Howdy partner, sit down! How's it going?", dictionary)
=> { "down" => 1, "go" => 1, "going" => 1, "how" => 2, "howdy" => 1, "it" => 2, "i" => 3, "own" => 1, "part" => 1, "partner" => 1, "sit" => 1 }
```

### [Stock Picker](https://github.com/TheOdinProject-gozooit/stock-picker)

Implement a method `#stock_picker` that takes in an array of stock prices, one for each hypothetical day. It should return a pair of days representing the best day to buy and the best day to sell. Days start at 0.

```ruby
> stock_picker([17,3,6,9,15,8,6,1,10])
=> [1,4]  # for a profit of $15 - $3 == $12
```

### [Bubble Sort](https://github.com/TheOdinProject-gozooit/bubble-sort)

Build a method `#bubble_sort` that takes an array and returns a sorted array. It must use the bubble sort methodology (using #sort would be pretty pointless, wouldn’t it?).

```ruby
> bubble_sort([4,3,78,2,0,2])
=> [0,2,2,3,4,78]
```

### [Tic Tac Toe](https://github.com/TheOdinProject-gozooit/tic-tac-toe)

Build a tic-tac-toe game on the command line where two human players can play against each other and the board is displayed in between turns.

1. Think about how you would set up the different elements within the game… What should be a class? Instance variable? Method? A few minutes of thought can save you from wasting an hour of coding.
2. Build your game, taking care to not share information between classes any more than you have to.

### [Mastermind](https://github.com/TheOdinProject-gozooit/mastermind)

Build a Mastermind game from the command line where you have 12 turns to guess the secret code, starting with you guessing the computer’s random code.

1. Build the game assuming the computer randomly selects the secret colors and the human player must guess them. Remember that you need to give the proper feedback on how good the guess was each turn!
2. Now refactor your code to allow the human player to choose whether they want to be the creator of the secret code or the guesser.
3. Build it out so that the computer will guess if you decide to choose your own secret colors. You may choose to implement a computer strategy that follows the rules of the game or you can modify these rules.

### [Event Manager](https://github.com/TheOdinProject-gozooit/event-manager)

This tutorial has been adapted from The Turing School's and Jump Start Lab's [Event manager](http://tutorials.jumpstartlab.com/projects/eventmanager.html) and updated to use GoogleCivic API.

The goal is to manipulate file input and output, read a CSV file and transform it into a standardized format, use the data to contact a remote service, populate a template with user data, access [Google's Civic Information API](https://developers.google.com/civic-information/) through the [Google API Client Gem](https://github.com/google/google-api-ruby-client) and user [ERB](http://rubydoc.info/stdlib/erb/ERB) for templating.

### Hangman

### Custom Enumerables

### Recursion

### Linked Lists

### Binary Search Trees

### Knights Travails

### Connect Four

### Ruby Final Project

## Javascript Foundations <img src="https://progress-bar.dev/67?title=Progress&width=180&color=333333" align="right">

### [Rock Paper Scissors](https://github.com/TheOdinProject-gozooit/js_rock-paper-scissors)

We’re going to make a simple implementation of grade-school classic “rock paper scissors”. First we’re just going to play the game from the browser console, but we will revisit this project in a later lesson and add a Graphical User Interface with buttons and text. Then we will revisit the project to add a simple UI.

### [Etch-a-Sketch](https://github.com/TheOdinProject-gozooit/js_etch-a-sketch)

In this project, we’re going to build a browser version of something between a sketchpad and an Etch-A-Sketch.

### [Calculator](https://github.com/TheOdinProject-gozooit/js_calculator)

Our final project is going to combine everything you’ve learned so far: you’re going to make an on-screen calculator using JavaScript, HTML, and CSS.
