Book: Software Architecture Fundamentals, Second Edition
Authors: Neal Ford, Mark Richards
Published by O'Reilly Media, Inc.

1. What is software Architecutre?
    - Definition
        >  The highest level concept of a system in its environment. The architecture of a software system is its orgnaziation
        or structure of significat componets interacting through interfaces those components being composed of successively smaller components and interfaces.
        > Comprises of following three things
            - Architecture Decisions
            - Design Principles
            - Overall Structure
            
	- Turning Requirement into a software by thinking on differect aspects
        - Security
        - Auditing
        - Logging
        - Data
        - Legality
        - Scalability
        - Many more...
    - Need to tradeoff between the functionality and non-functionality requriements

2. Understanding the Expectations of an Architect
    - 8 Core Expectation of an software architect
        1. Define the architecture and design principles to guide technology decisions for the enterprise
        2. Analyze Constantly the technology and software environment and recomand the changes or impromenmnts 
        3. Continously keepup with industry and technology trends
        4. Compliance with architecture 
        5. Have exposure to multiple and divirse technologies, platforms and environments
        6. Have certain level of business level expectation
        7. Posses exceptional interpersonal skills, including teamwork , facilitation and negotiation
        8. Understand the political climate of the enterprise and be able to navigate the politics

3. Thinking Like an Architect
    - Techinical breadth vs depth
        > Stuff you know
            - You have to maintian 
        > Stuff you know that you dont know
        > Stuff you dont know that you dont know
    - Archicture vs Desgin
	    - Archicture 	
		    a. Idenitfy Archicture Charactecistics 
			    - Like Scalability , Availability, etc
		    b. Identify Archicture pattern
			    - Microservices, Microkernal, Space based or event-driven
		    c. Identgify Core components of Archicture or building blocks
	    - Design
		    a. Idenfiy flow diagram, class diagram
		    b. UI Design
		    c. Database design
	> These two are not independent, they have to work togather to make it perfect
        - Use agile methodalogy to work closely with development team
	> Archecture is an ongoing process through the entire lifecycle of a product
    > Using spike identify various patterns/frameworks
    > Architect should do hands-on coding
        - Take fairly simple fubnctionality.
    > Do the code review, to ensure the complience of an architecure 

4. Identifying Architecture Characteristics
    - Scalability
    - Reliability
    - Performance 
    - availability
    - extensibility
    - maintainbility
    - agility
    - modularity
    - All non functional requrements
    - Add ability to any english work are all char of architecture
    Use case/ BUsniess case that defines Architecture Characteristics
 > Our business is contanctly changing to meet new demands of the marketplace
    - Agility
    - extensibility 
    - maintainbility 
    - modularity

 > Due to new regulrity requirements, its imperative that we complete end-of-day processing in time.
    - Performance
    - Scalability
    - Reliability
    
 > we need to faster time to market to remain compatitive
    - Agility
    - Testability
    - Deployability
    - Maintability
    - Modularity
> Our plan is to engage heavely in mergers and acquistitions in the next three years
    - Scalability
    - extensibility
    - openness
    - standars-based
    - agility
    - modularity
> we have very tight time and very tight budget for this project
    - FEASIBILITY


5. Analysing Architecture tradeoff
> ATAM( Architecture Tradeoff analysis method)
    - Create Architecture presentation
    - validate architecture and establish trade-off
    - Identify and mitigate risk
    - Get stake holder buy-in
> CBAM( Cost-Based analysis method)

6. Architecture Pattern
    - Simillar to design pattern but at very high level 

7. Understanding Layered Architecture
    - Big ball of mud Architecture Pattern
        - This is the Architecture that have no structure at all
    - Layered Archicture
        - Each of these layers closed
            > Request should go through each layer
            > Seperation of concern
            > Layers of isolation
        - To Solve sinkhole anti-pattern, make the layer as open to bypass that layer
        - Add open layer in layered Archicture if it is obsoultably needed, because adding open layer in layered Archicture defeats the purpose
    - Pattern Governence

8. Understanding Microkernel(plug-in) Architecture
    - Microkernel Architecture consists of core system and plug-in components
    - Architecture components
        - Core System 
            > Minimal functionality to run system
        - plug-in components
            > Standalone indepened module with specific additional rules or logic
    - Example:  
        - Eclipse
        - web browser
        
		
		
	