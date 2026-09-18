# Disability App Requirements

## Problem Statement

The application, named Disability App, will provide people with disabilities different tools and forms of support to make everyday tasks easier. A single app should provide accessible assistance tailored to the user's needs instead of assuming that one experience works for everyone.

## Goals

- Make everyday life easier for people with disabilities.
- Provide support tailored to different disability-related needs.
- Design the app around accessibility, flexibility, and user independence.

## Target Users

- People with disabilities who need practical support with everyday activities.

## Navigation And Organization

- The app will present Cognitive Mode, Motor Mode, and Speech Mode as separate buttons.
- Users will select the mode that matches the support they need.
- Each mode will display its features as separate buttons.
- Users will select an individual feature button to open and use that feature.
- The mode-and-feature button structure will keep the app organized and make available tools easier to find.

## Supported Disability Categories

The app will initially support needs associated with these categories:

1. Cognitive disorders
2. Motor problems
3. Speech impediments

## Features And Functionalities

### Cognitive Mode

#### Mental And Cognitive Accessibility Indicator

- The app will provide an accessibility indicator for places based on how supportive they are for people with mental or cognitive disabilities.
- The indicator will communicate accessibility in a simple, recognizable visual format inspired by the familiar blue wheelchair access sign.
- The indicator will describe mental and cognitive accessibility rather than physical accessibility.
- The criteria used to assign the indicator, including which place characteristics qualify as accessible, are to be defined.

#### Daily Routine Reminders

- The app will let users create reminders for daily routines.
- The app will send notifications to remind users when a routine or task is due.
- Users can remove saved routine reminders.
- Routine reminders repeat daily at the selected time while the app is open.
- The app requests browser notification permission when a reminder is saved and shows an in-app notification when the reminder is due.

#### Medication Tracker

- The app will let users record medications and the times they need to take them.
- The app will send simple notifications to remind users when a medication dose is due.
- Users can remove saved medication reminders.
- Medication reminders repeat daily at the selected time while the app is open.
- The app requests browser notification permission when a reminder is saved and shows an in-app notification when the reminder is due.
- The feature is intended to help users who forget medication doses, including users with ADHD-related memory challenges.
- Dose tracking, missed-dose handling, medication details, and safety boundaries are to be defined.

#### Cognitive Skills Games

- The app will provide games designed to exercise cognitive skills.
- Games will help users practice skills that may not have been learned or developed previously.
- Games should present learning and practice in an engaging, supportive format.
- Cognitive Skills Games will provide two separate game buttons: Number Memory and Item Recall.
- Only the game selected by the user will be displayed, and the user can switch between the two games by selecting the other button.
- The first game will be a number memory game that starts each round by showing a random sequence of four numbers as large, bubble-style number tiles.
- When the user begins typing their answer, the number sequence will disappear so the user recalls it from memory.
- A correctly completed sequence advances the next round by one number, starting at four numbers and continuing with five, six, seven, and higher.
- An incorrect sequence resets the game to a new sequence of four numbers.
- The game will give clear, supportive feedback after each attempt and let the user begin a new round.
- The next game will be an item-recall game that displays a chest containing approximately 10 varied, randomly selected items from a broad item bank.
- The chest and its items will remain visible for 30 seconds, with a bubble-style countdown displayed beside the chest.
- While the chest is open, the item-recall text box will remain hidden so the user cannot enter answers during the study period.
- When the 30-second countdown ends, the chest and its items will disappear and the text box will appear for item recall.
- The user will enter one item at a time and press Enter to submit each answer.
- Each correctly recalled item will allow the user to enter another item, and the game will count correct answers out of 10.
- If the user submits an item that is not in the chest, the round will end immediately and display a Game Over screen.
- The user will be able to start a new item-recall round using the Start Game button.
- Additional game types, target skills, accessibility controls, and the boundaries of any brain-training claims are to be defined.

#### Mood Check-In And Coping Exercises

- The app will send scheduled check-ins at user-defined intervals to ask how the user is feeling.
- Users will be able to respond with a mood or emotional state that reflects how they are feeling.
- Based on the response, the app will suggest exercises or actions intended to help the user feel better or stay better.
- The feature should be supportive, not critical, and should allow the user to choose their own pace.
- The exact interval options, mood categories, exercise library, and response logic are to be defined.

### Motor Mode

#### Body Check-In And Mobility Guidance

- The app will prompt users to check in on which parts of their body are not working as well as usual and which parts are working well.
- The check-in will use a multiple-choice format so users can select the areas they are experiencing discomfort, stiffness, weakness, or reduced movement in.
- The app will provide recommended mobility exercises or gentle movement routines tailored to the selected body areas and the user's reported pain or strain.
- The goal is to help users manage discomfort, reduce stiffness, and support overall mobility through guided movement.
- The exact body region categories, pain levels, exercise library, and recommendation logic are to be defined.

#### Physical Accessibility Indicator

- The app will provide an accessibility indicator for places based on how physically supportive they are for users with motor impairments.
- The indicator will use a familiar visual style similar to the standard blue wheelchair access sign.
- The indicator will represent physical accessibility rather than mental or cognitive accessibility.
- The criteria used to assign the indicator, including accessibility features such as ramps, wide paths, seating options, and suitable layouts, are to be defined.

#### Large Touch Targets And Expanded Layout

- Motor Mode will use a larger layout and more spacious interface design for users with tremors or reduced fine motor control.
- Buttons, controls, and interactive elements will be intentionally enlarged to improve tap accuracy and reduce accidental presses.
- The interface will prioritize clarity, separation, and accessibility over compact layouts.
- The required sizing thresholds, spacing rules, and target-device considerations are to be defined.

#### Persistent Voice Control

- The app will include a persistent voice-control button that remains available across the app at all times.
- The voice-control feature is designed for users with shaky or uncontrollable limbs who may not be able to interact with the interface through touch alone.
- Users will be able to speak commands to trigger core actions without relying on small or precise gestures.
- This feature is intended for broad app interactions and is separate from the dedicated speech support functionality in the speech mode section.
- The exact supported commands, microphone accessibility, and activation behaviors are to be defined.

### Speech Mode

#### Speech-Friendly Place Finder

- The app will help users find places that are easier to use for people with speech impediments.
- Results will focus on places where users can access services, communicate, and complete everyday tasks without speech being an unnecessary barrier.
- The accessibility criteria, place information, search behavior, and methods for verifying speech-friendly environments are to be defined.

#### Text-To-Speech Conversation Board

- The app will provide a conversation interface with a text bubble where users can type what they want to say.
- The interface will display auto-populating response options below the text area so users can answer without speaking or typing every response.
- Users will be able to change, add, and customize the suggested responses at any time.
- Instead of sending a written message, the app will read the selected or typed text aloud so the user can participate in a spoken conversation.
- The feature should support back-and-forth conversations while reducing the need for the user to speak.
- The exact response suggestions, text-to-speech controls, conversation flow, and customization experience are to be defined.

#### Guided Speech Lessons

- The app will provide basic speech lessons for users who want to practice producing words.
- Lessons will show visual mouth formations to demonstrate how sounds and words are made.
- The app will play example words aloud so users can hear the target pronunciation.
- Lessons should support step-by-step practice at a pace chosen by the user.
- The exact mouth-formation visuals, lesson content, word library, progression, and feedback methods are to be defined.

## Technical Considerations

### Deployment & Hosting

- The application is a static client-side web application built with HTML, CSS, and JavaScript.
- The web application is hosted using GitHub Pages directly from the `main` branch root folder (`/`).
- GitHub Pages automatically serves `index.html` as the main entry point.

