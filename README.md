# Apollo V.1

[Apollo](http://supersecretbanana.com/apollo-vis) is a study guide generator that creates interactive infographics based on user topic input. Apollo gathers data and arranges it into a responsive, gridded space-- outlining and interlinking hierarchically arranged information. It aims to provide:

	 - a brief linked outline / summary of important facts on the topic
	 - a space for users to collaboratively learn with others on a specifically generated guide (quiz, progress tracking, and leaderboard features)
	 - whenever possible, an interactive timeline of events

1 / Features List/

a. Unique URLS - all generated guides are saved through a unique URL that both new and old users can revisit. When a user chooses to edit over a generated guide - a new unique URL is assigned to the newly generated guide 

	a.1 - Guides generated off of other guides become a "child" to the "parent" or original guide. This aims to group together similar guides and archive versions of original and edited guides.
	
	a.2 Generated Guide Management - generated guides will contain the following details for archiving:
	
		- time and date of generation
		- unique URL
		- user who generated the guide*

2 / Structures and UI Outline / 

	a. Persistent Menu

	Displayed at the top part of the web screen and contains all needed settings and features

	b. Portrait Cards

	Portrait cards act as containers for interactive elements or images.
	
	- a square block that displays an image(portrait) by default
	- on hover: displays information on the image involving a header and body
	- on click: displays information + reveals scrollable content if overflow is needed
	- adequate padding from other content should be maintained to allow ease of interactivity and to increase legibility
    
	c. Timeline

3 / Users /

4 / Visual Language /

	a. Grid System
	
	b. Typography
	
	c. Color
	
	d. Study Guide Anatomy
	
5 / Print Translation /

	All available guides are designed to be easily exported as a PDF and printed into a letter-sized document. The four-grid default design for web screens follows the same format for print design-- allowing an easy translation to printed material. The information revealed on interactions (hidden from the digital version by default) will be readily displayed on the printed version, making the document information heavier than its interactive screen counterpart, but is outlined and arranged in an easy to navigate manner.
	
	The header - body relation will still be followed to maintain familiarity and consistency between the screen and printed versions. It should also follow 
	
	The aim of the print version is to allow users to access the generated guide without the need for bandwidth or screen time - It might be considered as a welcome alternative to help users go off screen, avoid it's readily available distractions, and focus on the information in the printed document.
	
6 / Data and Information / (further research on gathering methods needed -focus on reputable databases?)

	All data gathered is arranged in an easy to absorb manner. One of the goals of Apollo is to present gathered data to its users in its most simple form - allowing users to easily understand and learn a topic.
	
	Data Gathering:
	Data will be gathered from reputable art history databases online
	
	Popular examples:
	
		Proquest Design and Applied Arts Index (DAAI)
		
		Stylesight (WGSN)
		
		Communication and Mass Media Complete (EBSCO)
		
	
	Data Captured by User: (Potential Feature Idea)
	
		Users can also choose to use the notes they took during class and convert it into data through capturing their notes
		with the camera. Apollo translates the image into data and cross-checks the translated information to stored information
		on the database, revealing consistencies/inconsistencies and generating an interactive guide based off of it.
	
	Technical: 
	a
	* Allow users to scan in their notes - which will be translated to digital text and assessed by Apollo for integrity (this sounds like a new product and might work well on its own... "Athena?")
