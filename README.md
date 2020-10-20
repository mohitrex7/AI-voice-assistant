# voice_assist
Voice Assistant for Linux
System Requirement Specifications (SRS)
FOR
Voice Based Assistant for Linux

2. Problem Statement
To increase the usability of Linux system by designing Voice assistant which will help the user to do most of the tasks,
indirectly increasing easiness while handling the Linux system.
3. Overview
3.1 Background
Today in the Computer era, the world is focusing on easiness and reliability while handling Computer System. Lots of research
is going on for this. Voice Assistant is one of them. For Android, Google comes up with its own Google Assistant, Microsoft
come up with Cortana. But till the date, there is no Voice Assistant developed for Linux System. So, our team come up with
an idea to design the Voice Assistant for Linux based system.
3.2 Overall Description
The voice assistant we have designed can be controlled using voice as well as text input. The assistant can do a lot of work for
the user like opening and closing app, playing music, extracting information from the internet. Also, we have developed GUI
for our assistant through which you can control assistant via text as well as voice input.
4 Investigation & Analysis Methodology
4.1 System Investigation
Voice assistant can be controlled using voice as well as text. The input is then processed to find out the hot words or action
words. Then according to action words, the next action will be taken i.e. if user says ‘Open Firefox’ then ‘open’ will considered
as action word and process for opening the said application (i.e. Firefox) will be followed. The assistant will also show output
in text as well as voice format to give feedback to the user. To reduce the processing, we also stored some predefined audio
output so that assistant can directly play that sounds without text to speech processing.
4.2 Analysis Methodology
4.2.1 Feasibility study and requirements elicitation
Feasibility study for existing voice assistant will be done for extracting the feature and working of other voice assistants. The
comparison table will be made to compare feature and mode of working that can be use to determine which solution(s) are
most appropriate based upon the results of the comparisons.
4.2.2 System analysis
4.2.2.1 Perform an analysis of the problem using object-oriented techniques
An external view of the enterprise model of the voice assistant will be developed using Unified Modelling Language
(UML). This System Requirement Specifications documents will form part of the documentation for the project.
Some desired features of the new system include:
•
•
Ability to extract the data from website using web scrapping technique to answer the questions like
‘What is weather today?’
Ability to play the music, stored in hard disk, according to language said by user.
•
 Ability to open and close the application and folders
4.2.3 Process Flow Diagram
5 Constraints
5.1 Scalability
The voice assistant doesn’t not scale well to multiple requests (i.e. system cannot handle the both text as well as voice requests
at the same time.
5.2 Internet Issues
As for voice detection, assistant uses Google speech-to-text API, for voice detection, the system should be connected to the
working internet connection. Failure of internet connection may stop the working of the voice assistant.
5.3 Google Speech-to-text issues
Voice detection may get failed or may not be accurate for some words. The words which are not there in Google’s dictionary
may get failed to detect (like name of the person). Sometimes, word detection may get failed due to incorrect pronunciation or
incorrect/different language accent.
6 Operational Requirements
6.1 Help Desk Support
System users can access 24x7 assistance for questions that are technically related to problem facing, such as, slow application
response time, browser features, application errors, program interrupts problem, etc.
6.2 Application Services and Technical support
Programmers and software developers will have access to source code to locate bugs or system enhancements as
change necessary.
6.3 Application checks and Updates
Programmers and application developers will provide online checks and update patches on time to time. The patch will be
containing application new features and removal of bug and old unwanted parts.
7 Functional Requirements
AI Desktop partner offers a clear and accurate response to the user requirement.
1.
 User can enable and disable voice commands
2.
 The application should respond to which ever input it receives.
I.
 If the application doesn’t understand the input, it should return “Not Understood” statement .
II.
 If the application understands the input, it should respond with correct operation.
III.
 The application should use a voice recognition and typed input for further process.
3.
 The application should send data to user in the following ways:
I.
 The data can be sent as a voice response to the user.
II.
 The data can be sent as a text response to the user.
4. The application should be able to retrieve the information from the google with the help to scraper
5. User can control music player
I.
 User can choose song from the playlist that is available in the directory
II.
 User can play, pause the music.
6. User can open and close the application by voice or text input.
7. User can acquire system status.
8. User can learn how the application works
9. User can get general information about the application.
10. If the information is not found the application should open the web browser.
8. Input Requirements
8.1. Good quality mic.
User should have good quality mic for voice input. System should satisfy the microphone hardware driver requirements.
8.2. Speak clear
User should be audible and clear to the speech for the correct recognition on the command.
8.3. Text input
Incase if any of the above requirement is no satisfied, user can input their command in form of text.
9. Process Requirements
The following are requirements that the system must satisfy through which Desktop partner must be able to handle.
9.1 Supporting Software requirement
The system must have the required libraries and software installed in order to support all the services that
i.
 pyaudio
ii.
 SpeechRecognition
iii.
 gtts
iv.
 playsound
v.
 beautifulsoup4
vi.
 lxml
application supply.
9.2 Usability
The usability requirements of Smart Driver Assistant are the following:
i.
 The system must provide a simple and user-friendly GUI
ii.
 System must be robust to respond the command.
iii.
 System must be robust to user accent.
iv.
 The number of physical interactions should be minimum.
9.3 Performance
The performance requirements of Desktop partner are the following:
i.
 It should process voice command in less than 7 seconds.
ii.
 It should process the command response algorithm less in less time.
9.4. Use Case
9.4.1 UML Diagram
9.4.2 Activity Diagram
10 Output Requirements
10.1 Module 1-Open applications
This module deals with the basic operations related to the applications like open,close,search.When user fires command like
open app_name then application will be opened.Similar action for close.It includes any application(for ex.file
manager,browser etc).
10.2 Module 2-Play music module
Now as we got the processed input ,play music module can be implemented.Firstly,one folder is created which will contain
few songs in it.When the user requests for the song and if it is available in the folder itself then the song will be played.If song
is not available in the memory then the concept of web scraping(This is discussed in web scrapping part of the paper) is
implemented and song will be played.User has the facility to change song ,stop song whenever user wants .Also restart,play
previous one etc.
11 Hardware Requirements
11.1 Network
University network infrastructure (wired and wireless)
11.2 Production support systems
Web server computer(s) and related hardware support (back-up tapes, redundant drives, UPS, etc.)
12 Software Requirements
12.1 Operating System
➢
 Linux .
12.2 Python Setup
➢
 Web Scraping
➢
 Graphical User Interface(GUI)
➢
 Multithreading
➢
 OS related librarie
13 Deployment Requirements
9
