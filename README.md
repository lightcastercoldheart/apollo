# Apollo V.1

[Apollo](http://supersecretbanana.com/apollo-vis) is a study guide generator that creates interactive infographics based on user topic input. Apollo gathers data and arranges it into a responsive, gridded space; outlining and interlinking hierarchically arranged information. It aims to provide:

>- a brief linked outline / summary of important facts on the topic (see header card)
>- a space for users to collaboratively learn with others on a specifically generated guide (quiz, progress tracking, and leaderboard features)
>- whenever possible, an interactive timeline of events

**Terms:**

>*Cards*
>>are containers where generated data and interactive information will be populated into. They conform to a grid and change in height depending on the type and amount of information they are holding.

>>Header Card
>>-Header cards contain interactive elements that summarize the overall content of the generated guide.

>>1 - Guide Title
>>> Contains version information of generated guide (look into Github branching system)
>>> Provides information on available features for the guide (quiz, leaderboard, user tracking)
>>> Provides information on relative generated guides (will be able to show if it is based off of a parent guide as well as its children guides)

>>2 - Linked Content Outline
>>> Content throughought the guide is interlinked and opens up certain cards that contain the linked information on the outline
>>> This will act as the "anchor" or some sort of interactive table of contents that the user can click so they are directed to the content they need.
>>> because contents are divided into card sections that group information based on their relevance with each other, users can easily access the information they require without having to look through a bigger block of information currently irrelevant to their need.
>>> More information can be provided by linking guide content to reputable outside sources (online journal databases, scholar articles)

>>3 - Interactive Timeline
>>> Spans the entire width of the present document inside the header card. When present, the interactive timeline acts as a background for the linked content outline and guide title inside the header card.
>>> This will be helpful for time/date-rich guides that will allow users to easily go through information on the guide based on date




**1 / Features List/**

>a. Unique URLS - all generated guides are saved through a unique URL that both new and old users can revisit. When a user chooses to 
edit over a generated guide - a new unique URL is assigned to the newly generated guide 

>>a.1 - Guides generated off of other guides become a "child" to the "parent" or original guide. This aims to group together similar guides and archive versions of original and edited guides.
	
>>a.2 Generated Guide Management - generated guides will contain the following details for archiving:
	
>>>- time and date of generation
>>>- unique URL
>>>- user who generated the guide*

>b. Quiz
>>b.1 - Leaderboard
>c. Progress Tracking

**2 / Structures and UI Outline /**

>Simple to Complex - the idea behind the use of cards is to allow users to easily go through the main (or most important) information first, and then allow them to continue to learn more through expanding the cards and clicking through their links.

>>a. Persistent Menu

>>>Displayed at the top part of the web screen and contains all needed settings and features

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
