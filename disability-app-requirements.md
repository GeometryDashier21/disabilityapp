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
- Due reminders play an in-app alarm sound instead of relying on the default system notification sound.
- The alarm repeats every few seconds and shows a dismiss banner until the user dismisses it or a safety timeout is reached, so a reminder is not missed after only a few beeps.

#### Medication Tracker

- The app will let users record medications and the times they need to take them.
- The app will send simple notifications to remind users when a medication dose is due.
- Users can remove saved medication reminders.
- Medication reminders repeat daily at the selected time while the app is open.
- The app requests browser notification permission when a reminder is saved and shows an in-app notification when the reminder is due.
- Due medication reminders play an in-app alarm sound instead of relying on the default system notification sound.
- The alarm repeats every few seconds and shows a dismiss banner until the user dismisses it or a safety timeout is reached, so a reminder is not missed after only a few beeps.
- Due medication notifications include the dose note alongside the medication name.
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
- The mood check-in offers these mood options: happy, sad, calm, overwhelmed, tired, angry, stressed, excited, and nervous.
- Based on the response, the app will suggest exercises or actions intended to help the user feel better or stay better.
- Each mood draws from a large, locally generated pool of suggestion combinations (well beyond a handful of fixed options) so repeated check-ins for the same mood feel varied rather than repetitive, without requiring an external AI service.
- Selecting the same mood again shows a different suggestion each time until the full pool has been shown, then the pool reshuffles.
- The feature should be supportive, not critical, and should allow the user to choose their own pace.
- The exact interval options, mood categories, exercise library, and response logic are to be defined.

### Motor Mode

#### Body Check-In And Mobility Guidance

- The app will prompt users to check in on which parts of their body are not working as well as usual and which parts are working well.
- The check-in will use a multiple-choice format so users can select the areas they are experiencing discomfort, stiffness, weakness, or reduced movement in.
- Body area options include: Neck, Shoulders, Elbows, Wrists, Hands, Back, Hips, Knees, Ankles, and Feet.
- The app will provide recommended mobility exercises or gentle movement routines tailored to the selected body areas and the user's reported pain or strain.
- Each body area draws from a large, locally generated pool of specific, named exercises and stretches for that area (not a generic "range of motion" message) so repeated check-ins for the same area feel varied rather than repetitive, without requiring an external AI service.
- Each exercise/stretch suggestion includes clear, step-by-step instructions (positioning, reps, and hold times) so the user knows exactly how to perform it.
- Selecting the same body area again shows a different suggestion each time until the full pool has been shown, then the pool reshuffles.
- For each selected body area, the app displays only the one randomly suggested exercise, along with an animated illustration of a person performing that exact suggested movement (not a browsable list of every possible stretch).
- The animated illustration is shown on a ground/floor line so the figure appears grounded during the movement.
- Each animation starts paused with its own Play/Pause button, and loops continuously once played, so the user has time to scroll to it and watch without racing a short one-shot clip.
- The goal is to help users manage discomfort, reduce stiffness, and support overall mobility through guided movement.
- The exact pain levels and recommendation logic beyond area selection are to be defined.

#### Physical Accessibility Indicator

- The app will provide an accessibility indicator for places based on how physically supportive they are for users with motor impairments.
- The indicator will use a familiar visual style similar to the standard blue wheelchair access sign.
- The indicator will represent physical accessibility rather than mental or cognitive accessibility.
- The criteria used to assign the indicator, including accessibility features such as ramps, wide paths, seating options, and suitable layouts, are to be defined.

#### Large Touch Targets And Expanded Layout

- Motor Mode will use a larger layout and more spacious interface design for users with tremors or reduced fine motor control.
- Buttons, controls, and interactive elements will be intentionally enlarged to improve tap accuracy and reduce accidental presses.
- The interface will prioritize clarity, separation, and accessibility over compact layouts.
- The Large Touch Layout screen provides a working slider (100%-160%, in 10% steps) that live-resizes every button and control across the entire app (not just Motor Mode), with a label showing the current percentage.
- The chosen touch target size is saved on the device and reapplied automatically the next time the app loads.
- The required spacing rules and target-device considerations beyond the slider range are to be defined.

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
- The conversation board will not show built-in suggested phrases between the message field and the speak control.
- Users can save a typed response as a quick response on the device.
- Saved quick responses are displayed as selectable buttons. Selecting one fills the conversation text bubble and reads the response aloud.
- Users can remove saved quick responses, and the response disappears from the list immediately.
- Instead of sending a written message, the app will read the selected or typed text aloud so the user can participate in a spoken conversation.
- The feature should support back-and-forth conversations while reducing the need for the user to speak.
- The exact response suggestions, text-to-speech controls, conversation flow, and customization experience are to be defined.

#### Guided Speech Lessons

- The app will provide basic speech lessons for users who want to practice producing words.
- Lessons will provide multiple word sets, with 20 words in each set, and the app will support adding more sets over time.
- Lessons will show a simple, recognizable mouth formation for every sound or mouth-movement part of the selected word at the same time.
- Selecting any word part, including parts after the first, will update the main mouth formation to match that part.
- The mouth formation legend will identify the colors as: Red - mouth; Pink - tongue; Grey - lips.
- The app will play example words aloud so users can hear the target pronunciation.
- Users can choose multiple playback speeds for example words, from very slow practice through 3x speed.
- Lessons should support step-by-step practice at a pace chosen by the user.
- The exact mouth-formation visuals, lesson content, word library, progression, and feedback methods are to be defined.

## Technical Considerations

### Deployment & Hosting

- The application is a static client-side web application built with HTML, CSS, and JavaScript.
- The web application is hosted using GitHub Pages directly from the `main` branch root folder (`/`).
- GitHub Pages automatically serves `index.html` as the main entry point.

