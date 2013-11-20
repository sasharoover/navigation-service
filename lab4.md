#Introduction
##What is the Project?

- Guitar learning tool version 2.0

Overall description of the product (=what is it? can you understand it?)
- To teach people how to play guitar

Target audience?
- people/humans

The situation?
- making people learn to play guitar

Motivation?
-The goal is to have unskilled users be able to pick up a 
 real guitar and know how to play notes, chords, and scales
 just by using our app.

Structure
-Guitar lessons for the learning and practice of guitar playing.
-A metronome for practice of guitar playing.
-A list of music terminology to aid the unfamiliar user.
-A tool to aid in the tuning of a user’s guitar.
-A scale finder to display different guitar scales for the user to learn.
-A chord finder to display chords for the user to learn.

Compare the structure of the document with the template provided for the course group work. 
How does it differ? Is there more? Less? 
- It is more like the wikipedia document structure
- It has less details and pictures


#Use Cases
What the system (will) do?
- The bulk of the software is feature based, and not necessarily functionality based. 
This means that all of the use cases are equally as important.
Features
  *Metronome 
  *Lessons
  *Tuner
  *Scale Finder
  *Music Dictionary
  
  
Use case diagram
![ScreenShot](https://users.metropolia.fi/~jeremyk/SoftEng/UC1.JPG)


General structure of the system
- The Use-Case View captures system functionality as seen by user(s).
The use case diagram provided shows the system behavior and the functionality it 
must provide for the user. The diagram illustrates the system’s intended functions, its surroundings,
and relationships between use cases and actors.

- The Logical View consists of the design and analysis models. 
The design model was used in this document and includes all collaborating 
classes, organized as activities. The analysis model is unused.

- The Process View consists of the process and threads that form the 
system’s concurrency and synchronization mechanisms, as well as their interactions. 
Threads and processes are modeled activities related to a main base activity with subclasses.

- The Deployment view will be excluded, as the software is intended 
to be a standalone application capable of running on Android devices.
 

#Functional 
- Guitar Lesson: Notes
*REQ-1: The software must respond to multiple touches that correspond to the 
      correct finger positions for a specific note.
*REQ-2: The software will allow a user to move forward if they are unable to complete a note via a skip button.
*REQ-3: The software will inform the user when they have duplicated a note unsuccessfully.

-Guitar Lesson: Chords
*REQ-1: The software must respond to multiple touches that correspond to the correct finger 
    positions for a specific chord.
*REQ-2: The software will allow a user to move forward if they are unable to complete a chord via a skip button.
*REQ-3: The software will inform the user when they have duplicated a chord unsuccessfully.

-Music Dictionary
*REQ-1: The software must allow the user to easily find the term that they are looking for in the music dictionary (assuming it is in the dictionary). This will be accomplished by allowing multiple search techniques.
*REQ-2: Each stage in the search must have an option to return to the application’s
  main menu so that it may again be reached.
*REQ-3: If a term is not found by the search tool, the user must be informed of such.

-Metronome
REQ-1: The software must allow a user to start or stop the metronome on demand. 
REQ-2: The software must allow the user to adjust the tempo of the metronome.
REQ-3: The software must provide a means to return from the metronome to the main menu.

-Guitar Tuner
*REQ-1: The software must allow a user to pick a string to tune at any time.
*REQ-2: The software must allow the user to re-listen to the correct pitch for a string at 
  any time after selecting that string.
*REQ-3: The software must provide a means to return from the guitar tuner to the main menu.


-Scale Finder
*REQ-1: The software must allow the user to exit at any moment.
*REQ-2: The software must include multiple drop-down lists to select the keys.
*REQ-3: The software must display the guitar neck complete with fingerings when the user selects a specific scale pattern and key.
*REQ-4: The user must be able to go back at any moment.

#non-functional requirements
- Performance Requirements
  * The software should be lightweight enough so that it can be run on mobile devices.
- Safety Requirements (N/A)
- Security Requirements (N/A)
- Software Quality Attributes


How does (will) it look?
- No UI examples and mockups. Only explanation

#No Process model

#Our point of view
- It is good and better than any other document we have seen
- There are few diagrams but they are complicated

