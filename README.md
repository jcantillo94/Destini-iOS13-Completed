INITIAL BRANCH OWNED BY APPBREWERY, This fork is my modified rendition of the intended format/design pattern and functionality. 

#  Destini

You as the user will read a story and will make one of two choices that will progress the story onto subsequent progressions displayed via text. You will be required to make additional choices between two decisions until the story ends.


## Purpose

This fork was created according to the guidance of Appbrewery's iOS13 & Swift - The Complete iOS App Development Bootcamp's Section 10: iOS APP Design Pattern Challenge. 

The intent here was to construct the functionality of an app that guides users on a story based on one of two choices presented to them via the UI. Either choice would present a new body of text presenting the progression of the story based on their choice within the greater encompassing UI element on the screen. The user will then continue to decide between one of two choices until the story ends. Once the story ends, the UI will cycle back to the beginning of the story thus allowing users to experiement with different choices if they wish.

<<<<<<< HEAD
## What I Learned
 - a recap on the purpose and utility behind a Model-View-Control design pattern*
 - using struct's for their properties and methods for the purpose of being initialized so that instances of them can be used for the use-case of a program
 - the concept of a 'Brain' i.e. StoryBrain.swift - a struct that handles the unqiue instances of an underlying struct with it's own properties and methods
 - Using Github and Git to intently fork an established repo onto my own account. This was my first time attempting so and required a inquisitive process to get it done using console commands git remote ...
=======
## Story Strings
```
         Story(
            title: "Your car has blown a tire on a winding road in the middle of nowhere with no cell phone reception. You decide to hitchhike. A rusty pickup truck rumbles to a stop next to you. A man with a wide brimmed hat with soulless eyes opens the passenger door for you and asks: 'Need a ride, boy?'.",
            choice1: "I'll hop in. Thanks for the help!", choice1Destination: 2,
            choice2: "Better ask him if he's a murderer first.", choice2Destination: 1
        ),
        Story(
            title: "He nods slowly, unfazed by the question.",
            choice1: "At least he's honest. I'll climb in.", choice1Destination: 2,
            choice2: "Wait, I know how to change a tire.", choice2Destination: 3
        ),
        Story(
            title: "As you begin to drive, the stranger starts talking about his relationship with his mother. He gets angrier and angrier by the minute. He asks you to open the glovebox. Inside you find a bloody knife, two severed fingers, and a cassette tape of Elton John. He reaches for the glove box.",
            choice1: "I love Elton John! Hand him the cassette tape.", choice1Destination: 5,
            choice2: "It's him or me! You take the knife and stab him.", choice2Destination: 4
        ),
        Story(
            title: "What? Such a cop out! Did you know traffic accidents are the second leading cause of accidental death for most adult age groups?",
            choice1: "The", choice1Destination: 0,
            choice2: "End", choice2Destination: 0
        ),
        Story(
            title: "As you smash through the guardrail and careen towards the jagged rocks below you reflect on the dubious wisdom of stabbing someone while they are driving a car you are in.",
            choice1: "The", choice1Destination: 0,
            choice2: "End", choice2Destination: 0
        ),
        Story(
            title: "You bond with the murderer while crooning verses of 'Can you feel the love tonight'. He drops you off at the next town. Before you go he asks you if you know any good places to dump bodies. You reply: 'Try the pier.'",
            choice1: "The", choice1Destination: 0,
            choice2: "End", choice2Destination: 0
        )
```
>>>>>>> 923d988557cb8b4e395ed39a2b072c57551950c5


* In my own words, MVC allows for 3 different components of a system/program to be responsible for data, how input and outout is both recieved and presented back to an end-user and how input is processed between the two other components (Model and View) in one respective componenet - the Controller
