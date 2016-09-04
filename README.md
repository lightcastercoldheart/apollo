# Apollo V.1

[Apollo](http://supersecretbanana.com/apollo-vis) is a study guide generator that creates interactive infographics based on user topic input. Apollo gathers data and arranges it into a responsive, gridded space; outlining and interlinking hierarchically arranged information. It aims to provide:

>- a brief linked outline / summary of important facts on the topic (see header card)
>- a space for users to collaboratively learn with others on a specifically generated guide (quiz, progress tracking, and leaderboard features)
>- whenever possible, an interactive timeline of events

**Terms:**

>*Cards*
>>are containers where generated data and interactive information will be populated into. They conform to a grid and change in height depending on the type and amount of information they are holding.

>>Header Card
>>-Header cards contain interactive elements that summarize the overall content of the generated guide. They are placed on top of each generated guide, providing users with anchored links that can easily direct them to a particular topic/card they are interested in

>>1 - Guide Title
>>> Contains version information of generated guide (look into Github branching system)
>>> Provides information on available features for the guide (quiz, leaderboard, user tracking)
>>> Provides information on relative generated guides (will be able to show if it is based off of a parent guide as well as its children guides)
>>> Title subheaders will provide users with information on its parent guide / system guide (more on back-end information, maybe a tree that shows the parent-child system of the guide and their connections)


>>2 - Linked Content Outline
>>> Content throughought the guide is interlinked and opens up certain cards that contain the linked information on the outline
>>> ?? Linked outlines as a persistent popup menu for smaller screens?

>>> This will act as the "anchor" or some sort of interactive table of contents that the user can click so they are directed to the content they need.

>>> because contents are divided into card sections that group information based on their relevance with each other, users can easily access the information they require without having to look through a bigger block of information currently irrelevant to their need.

>>> More information can be provided by linking guide content to reputable outside sources (online journal databases, scholar articles)

>>3 - Interactive Timeline
>>> Spans the entire width of the present document inside the header card. When present, the interactive timeline acts as a background for the linked content outline and guide title inside the header card. 

>>> This will be helpful for time/date-rich guides that will allow users to easily go through information on the guide based on date

>>> Aggregated data with dates or information that can be displayed as a timeline
will be generated as an interactive timeline for the header. If no timeline data is included in the information gathered, the interactive timeline is disabled and
replaced by an image or color background depending on the most relevant data that can help generalize the type of information generated on the guide.

>> Topic Cards
>>> Information generated into the guide are separated into topics. The generator recognizes keywords and categorizes them into a topic card that holds relevant information users can easily have access to.

>>> The size of a topic card depends on the  amount of information it holds. Depending on screen size, it's width can also span from 4 grids to 1. Width of the cards will depend on several factors: Width of images + amount of text, size and layout of the previous card it follows

>>*Card Layout and Generated Arrangement*
>>> Topic cards have several layout options that the generator can randomly select through a criteria. The goal for varied layouts is to provide users with a dynamic and less uniform approach so as to differentiate each card, and not make it look too similar. This follows graphic design and layout rules for a more
dynamic overall guide design.

>>> Header Card Layout will strictly depend on the amount of overview informationa available so as to develop a more uniform look across all generated guides. Title information and timeline backgrounds will be the varying elements that would make the header cards look distinct from other guides.

>>> Parent/Child Guide Layouts
>>> Parent and children guides will have similarities and differences to avoid confusion while also maintain a level of familiarity and connection. Colors and layouts will be maintained while the changes made on each of the guide will be highlighted and it's closest connecting guide linked to easily see connected guide versions.

>>>Constants and Variables
>>>Constants
>>> * Topic card title
>>> * image block size (expanded/unexpanded)
>>> *
>>>Variables
>>> * Text and image layout

**1 / Features List/**

>a. Unique URLS - all generated guides are saved through a unique URL that both new and old users can revisit. When a user chooses to  edit over a generated guide - a new unique URL is assigned to the newly generated guide 

>>a.1 - Guides generated off of other guides become a "child" to the "parent" or original guide. This aims to group together similar guides and archive versions of original and edited guides.
	
>>a.2 Generated Guide Management - generated guides will contain the following details for archiving:
	
>>>- time and date of generation
>>>- unique URL
>>>- user who generated the guide*

>b. Quiz
>>> The quiz feature locks the cards in a guide. To unlock the cards and access more information, the user must answer a question that is related to an unlocked card in the guide. This will help users test out whether they've learned something from the guide and help them learn more about the study guide's generated information.
>>> The quiz feature can be the flipside of the card that users need to answer correctly before it can finally be flipped over to reveal the next information
This is sort of similar to index card guides students use as study aides. (look into how students use study aide materials specifically index cards)

>>b.1 - Leaderboard
Leaderboarding is a feature that can be activated for each guide. This feature shows which users have taken the quiz and have unlocked the most locked cards in the guide. This feature is only available if the quiz feature is activated.

>c. Progress Tracking

**2 / Structures and UI Outline /**

>Simple to Complex - the idea behind the use of cards is to allow users to easily go through the main (or most important) information first, and then allow them to continue to learn more through expanding the cards and clicking through their links.

>>a. Persistent Menu

>>>Displayed at the top part of the web screen and contains all needed settings and features. 

>>> On smaller screens, the persistent menu turns into a persistent pop-up menu to make up more space for card information. 

>>b. Portrait Cards

>>>Portrait cards act as containers for interactive elements or images.
	
>>>>- a square block that displays an image(portrait) by default
>>>>- on hover: displays information on the image involving a header and body
>>>>- on click: displays information + reveals scrollable content if overflow is needed
>>>>- adequate padding from other content should be maintained to allow ease of interactivity and to increase legibility
    
>>d. Header Cards
	
>>>Header cards usually populate the entire span of the top part of the guide and contains the following interactive elements:
	
>>>>d.1 Guide Title

>>>>d.2 Linked Content Outline
	
>>>>d.3 Timeline

**3 / Users /**

**4 / Visual Language /**

>a. Grid System
	
>b. Typography
	
>c. Color
	
>d. Study Guide Anatomy
	
**5 / Print Translation /**

>All available guides are designed to be easily exported as a PDF and printed into a letter-sized document. The four-grid default design for web screens follows the same format for print design-- allowing an easy translation to printed material. The information revealed on interactions (hidden from the digital version by default) will be readily displayed on the printed version, making the document information heavier than its interactive screen counterpart, but is outlined and arranged in an easy to navigate manner.
	
>The header - body relation will still be followed to maintain familiarity and consistency between the screen and printed versions. It should also follow 
	
>The aim of the print version is to allow users to access the generated guide without the need for bandwidth or screen time - It might be considered as a welcome alternative to help users go off screen, avoid it's readily available distractions, and focus on the information in the printed document.
	
**6 / Data and Information /** *(further research on gathering methods needed -focus on reputable databases?)*

>All data gathered is arranged in an easy to absorb manner. One of the goals of Apollo is to present gathered data to its users in its most simple form - allowing users to easily understand and learn a topic.
	
>>Data Gathering:
	Data will be gathered from reputable art history databases online
	
>>Popular examples:
	
>>>Proquest Design and Applied Arts Index (DAAI)
		
>>>Stylesight (WGSN)
		
>>>Communication and Mass Media Complete (EBSCO)
		
	
>>Data Captured by User: (Potential Feature Idea)
	
>>>Users can also choose to use the notes they took during class and convert it into data through capturing their notes with the camera. Apollo translates the image into data and cross-checks the translated information to stored information on the database, revealing consistencies/inconsistencies and generating an interactive guide based off of it.
	
>>Technical: 
	
>>>* Allow users to scan in their notes - which will be translated to digital text and assessed by Apollo for integrity (this sounds like a new product and might work well on its own... "Athena?")

---
LOGS

------
090116
------
I have decided to start a progress log for Apollo. This is the first day I am recording a daily journal as to how Apollo is progressing (may it be slowly, or no progress at all - in which case, the log would involve some self humiliation so as to embarrass myself if anyone else ever decides to read this. If you are reading this and you're not me from the future, thank you and sorry for any profanities you might encounter if you ever choose to read further... If you are me from the future, find something else more productive to do you fuckity fuck fuck! )

------
090216
------
* Added layout option descriptions and outlined "topic cards." Thinking about how
the generator will select one preset layout over another. Will need to study layout options and sketch out the possibilities for each card width and height as their behaviors when interacted with. Also, not feeling well and trying hard not to sneeze in the library 

------
090316
------
* Started initial designs for layout cards (needs to be tested). Thinking about adding interactions and showing expanded versions of topic card. Might need a higher fidelity prototype for showing them...


