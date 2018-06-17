
Bowling Challenge
=================

### [Makers Academy](https://makers.tech/)::[Week 5/6 Weekend Challenge](https://github.com/makersacademy/bowling-challenge)


## Setup Instructions :

```
  + Fork this repo;
  + Do what you like, it's your life ¯\_(ツ)_/¯
```

## Task Constraints :

```

  + This is not a bowling game, it's a bowling scorecard simulator
  + The code base for this site is JavaScript
  + All TTD is done with Jasmine 3.1.0, located in the lib folder
  + Tests can be run by opening the SpecRunner.html file in a browser
  + Opening the ScoreCard.html file will run the simulator in a browser
  + All rolls will be manually inputted by the user, similar to in a real game

```
## Bowling Rules :

```

  + The game consists of 10 frames
  + In each frame, the player has 2 opportunities to knock down 10 pins
  + The score for the frame is the total number of pins knocked down
  + There are bonuses for ‘strikes’ [ x ] and ‘spares’ [ / ]
  + A spare is when the player knocks down all 10 pins within both allotted frame tries
    + The bonus for a spare is the number of pins knocked down on the next roll
  + A strike is when a player knocks down all 10 pins on the first try
    + The bonus for a strike is the value of the next 2 balls rolled
  + In the 10th frame, a player who rolls a spare or strike are allowed to roll …
    … the extra balls to complete the frame
    + No more than 3 balls can be rolled in the 10th frame

```
[Video Explanation](https://www.youtube.com/watch?v=aBe71sD8o8c)


## Sample ScoreCard
![Ten Pin ScoreCard Example](images/BowlingScoreCard.jpg)


## User Stories :

```

  TODO

```

## Logic Diagram :


## UML Class Diagrams :


### Notes and Optional Extras :

In any order you like:

* Create a nice interactive animated interface with jQuery.
* Set up [Travis CI](https://travis-ci.org) to run your tests.
* Add [ESLint](http://eslint.org/) to your codebase and make your code conform.

You might even want to start with ESLint early on in your work — to help you
learn Javascript conventions as you go along.


## Code Review

In code review we'll be hoping to see:

* All tests passing
* The code is elegant: every class has a clear responsibility, methods are short etc.

Reviewers will potentially be using this [code review rubric](docs/review.md).  Note that referring to this rubric in advance may make the challenge somewhat easier.  You should be the judge of how much challenge you want.
