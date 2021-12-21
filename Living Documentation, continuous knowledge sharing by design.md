#cyrille-martraire

Beyond making use of technology, writing software is a lot about making decisions based on knowledge. When you don't have enough knowledge, you have to make learning experiments and collaborate with other people to discover new knowledge. This takes time, which also means this knowledge is expensive and has value. Going fast is all about learning faster when you need new knowledge or about quickly recovering any prior valuable knowledge whenever there was some. 
#learning #pursuit-of-knowledge #knowledge  #growth #value-and-worth #cybernetics 

[Certain situations lead] to redundant knowledge: You end up with the original source of truth (usually the code) and a bunch of copies that duplicate this knowledge in various forms. Unfortunately, when one artifact changes - for example, the code - it is hard to remember to update the other documents. As a result, the documentation quickly becomes obsolete, and you end up with incomplete documentation that you cannot trust. How useful is that documentation?
#documentation #consistency 

Enterprise knowledge management solutions are the places where knowledge goes to die. Consider these: Enterprise wikis, SharePoint, large MS Office documents, shared folers, ticketing systems and wikis with poor search capabilities. These approaches to documentation often fail either because they make it too hard to find the right information or because it's too much work to keep the information up to date or both. They promote a form of write-only documentation, or write-once documentation.
#business #sorting-and-searching #writing #reading 

Documentation can be toxic when misleading.
#harm 

Software development is all about knowledge and decision-making based on that knowledge, which in turn creates additional knowledge. The given problem, the decision that was made, the reason it was made that way, the facts that led to that decision, and the considered alternatives are all knowledge.
#architecture-decision-records #writing #narrative 

Software design can last a long time. It can last long enough to forget about previous decisions made, as well as their contexts. It can last long enough for people to leace, taking with them their knowledge, and for new people to join, lacking knowledge. Knowledge is central to a design activity like software development.
#knowledge #design #architecture 

Most of the time this design activity is, for many good reasons, a team effort involving more than one person. Working together means making decisions together or making decisions based on someone else's knowledge.
#decision-making #collaboration #teamwork #multidisciplinary-teams 

Something unique with software development is that the design involves not only people but also machines. [...] Having a computer understand source code is not the hard part, though. Even inexperienced developers usually manage to succeed at that. The hardest part is for other people to understand what has been done so that they can then do better and faster work.
#humans-and-machines #language 

Knowledge primarily comes from conversations.
#knowledge #dialogue 

Any form of documentation has to consider the cost of maintenance and make as close to zero as possible. For stable knowledge, traditional methods of documentation work. But with frequently changing knowledge, writing text and updating it after every change is just not an option. the effect of acceleration in the software industry is that we want to be in a position to evolve the software very quickly. The speed is such that it's impossible to spend time writing pages and pages of documentation, and yet we want all the benefits of documentation.
#care #responsibility

Lack of knowledge manifests as two costs:
- Wasted time: That time could have been better invested in improving something else.
- Suboptimal decisions: Other decisions could have been more relevant, or cheaper in the long term. 
These two expenses compound over time. 
#consequences 

I hope future programming languages will recognize the need to represent not only the behavior of the code but also the bigger mental model of the programmers, of which the code is a consequence.
#mental-models #sapir-whorf #linguistic-relativity 

There's also a logistic aspect to documentation. It's about transferring knowledge in space between people and also about transferring it over time, which technical people call persistence or storage. [It's like] shipment and warehousing of goods, where the goods are knowledge.
#product #documentation #knowledge #spatio-temporal-relations #time 

The development tenure half-life is 3.1 years, whereas the code half-life is 13 years. Documentation has to help with this mismatch. (data from Rob Smallshire, sixty North blog)
#work #data 

Transferring knowledge from the brain of a technical person to the brains of non-technical people is a matter of making the knowledge accessible.
#translation #accessibility #equity 

Persistent documentation comes in two flavors: external and internal.
With external documentation, knowledge is expressed in a form that has nothing to do with the chosen implementation technologies of the project. This is the case of the traditional forms of documentation, with separate Microsoft Office documents on shared folders or wikis with their own databases.
An advantage of external documentation is that it can take whatever format and tool is most convenient for the audience and for the writers. The drawback is that it's extrmely hard, if not impossible, to ensure that external documentation is up-to-date with respect to the latest version of the product. External documentation can also simply be lost.
In contrast, internal documentation directly represents knowledge by using the existing implementation technology. Using Java annotations or naming conventions on the language identifiers to declare and explain design decisions is a good example of internal documentation.
the advantage of internal documentation is that it's always up-to-date with any version of the product, as it's part of it's source code. Internal documentation cannot be lost because it's embedded within the source code itself. It's also readily available and comes to the attention of any developers working on the code just because it's under their eyes. Internal documentation also enables you to benefit from all the tools and all the goodness of your fantastic IDE, such as autocomplete, instant search, and seamless navigation within and between elements. The drawback is that your expression of the knowledge is limited to the possible extension mechanisms built into the language. [...] Another big drawback is that the knowledge expressed as internal documentation is not readily accessible to non-developers. However, it is possible to work around that limitation with automated mechanisms that extract the knowledge and turn it into documents that are accessible to the right audience.
#documentation #automation #linguistics 

You can trust documentation only if there is a mechanism to guarantee its accuracy.
#trust #dependence 

A good approach for documentation is a matter of design. It takes design skills to design documentation that is always accurate, without slowing down the software development work.
#design #multi-hyphenate #interdisciplinary #information-architecture #user-experience #interdependence 

Efficient documentation must target an identified audience. Even documentation about things "that everyone should know" has to target an audience, such as "nontechnical people with only a superficial knowledge of the business domain". 
#audience #writing 

The first question of documentation: Do we really need this documentation? the other first question of documentation: Do we really need this documentation NOW?  [...] It is important to use a number of strategies to determine when it's important to do documentation:
- Just-in-time: Add documentation only when really needed.
- Cheap upfront: Add a little documentation now, at a very low cost.
- Expensive upfront: Add documentation now, even if it takes time to create it.

If knowledge is only in the heads of the people, then it needs to be encoded somewhere - as text, code, metadata, some something else. If the knowledge is already represented somewhere, the idea is to use it (knowledge exploitation) or re-use it (knowledge augmentation) as much as possible.
#efficiency #knowledge 

Living document: A document that evolves at the same pace as the system it describes.
#semantics #dependence #reflexive-praxis 

Explicit quality attributes: Friends don't let friends guess the quality attributes for which a system was designed.

It's almost useless to document a solution without explaining the problem it attempts to solve.
#architecture-decision-records #problemsolving 

A project is interesting it is addresses a problem for which there is no standard solution. The project must discover how to solve the problem through continuous learning and a lot of knowledge crunching while exploring the domain. As a consequence, the resulting code will change all the time, from small changes to major breakthroughs.
#problemsolving #agile #continuous-improvement #work 

"Try, Try Again" requires change-friendly documentation.
#agile #documentation #mutability #change #flexibility 

Your investment in learning living documentation is also an investment in learning some aspects of domain-driven design. Learn one, and you learn half of the other for free!
#domain-driven-design #design 

Living documentation is all about paying attention to the knowledge involved in software making. Some knowledge is more important than other knowledge, and the most important knowledge is almost surely already somewhere in a project's artifacts. The goal, and the fun, of living documentation is to recognize the valuable knowledge, where it already is, and determine what may be missingg and how often it changes in order to best benefit from it with minimal expense. In other words, it is about designing a system of knowledge within your code base itself, and it requires design skills, just like coding!
#interdisciplinary #coding #design #systems-thinking 

BDD scenarios describe the behavior of an application, but the source code of the application also describes this behavior: The scenarios and the source code are redudant with each other.
On the one hand, this redundancy is good news: Scenarios expressed in pure domain language, if done properly, are accessible to nontechnical audiences such as business people who could never read code. However, this redundancy is also a problem: If some scenarios or parts of the code evolve independently, then you have two problems: You must determine whether to trust the scenarios or the code, and (a bigger problem), you must in some way know that the scenarios and the code are not in sync. 
This is where a reconciliation mechanism is needed. In the case of BDD, you can use tests and tools like Cucumber or SpecFlow. these tools act like a roberval balance between both redundant pieces of knowledge.
#balance #reconciliation-mechanism #automation #coding 

BDD has shown that it is possible to have accurate documentation that is always in sync with the code by doing the specification work more carefully. BDD is a canonical case of living documentation, and all the core principles of living documentation are already present in BDD (Collaborative, Low-effort, Reliable thanks to a reconciliation mechanism)

When knowledge is repeated in different places, you need to know where to find the knowledge you can trust.
#trust #ssot #repetition

Diverse facts put together become useful knowledge.
#knowledge #pursuit-of-knowledge #learning #value-and-worth #transformation 

Even if the knowledge is split into many little parts, it's still desirable to consider all those little bits as the authoritative single sources of truth. The derived consolidated knowledge is therefore a special case of published document extracted from many places.
#parts-and-whole #ssot 

More and more of what we do every day gets codified by talented practitioners into patterns, techniques, and practices. And all that knowledge is properly documented in books, blog posts, and conference talks and workshops around the world. this is ready-made documentation that's readily available, for free or for the price of a book or workshop.
#social-networks #abstraction #patterns #pursuit-of-knowledge #generosity #literature 

It is safe to say that if you can think about it, somebody has already written about it. (context: talking specifically about patterns, naming standards, etc)

The power of a standard vocabulary: Ludwig Wittgenstein - "He who controls vocabulary controls thought."
#semantics #construction-of-reality #linguistics #neurolinguistic-programming 

Each mature industry has its own rich jargon because using such understood jargon is an efficient way to communicate.
#communication #relative-correctness #linguistic-relativity #domain-driven-design #social-constructs 

Ubiquitous language is extremely helpful in documentation. If you know what you're doing and you know what it's called in the industry, you can just insert a reference to the industry standard, and you have achieves extensive documentation at low cost.
Patterns and pattern languages are particularly effective at packing ready-made knowlege into re-usable documentation. Patterns really are canned documentation.
#patterns #linguistic-relativity #sapir-whorf #efficiency 

Many articles have harshly criticized code that is full of patterns. However, I think they miss the point: You should learn as many patterns as you can. The idea is not to learn patterns in order to use them, though they can be useful; instead, the points is ot know many patterns in order to know the standard names of what you're doing. In this view, 100% of the code could, and should, be described by the means of patterns.
#pursuit-of-knowledge #problemsolving 

Better integration between tools also helps simplify human tasks, which reduces the need for manual documentation of the tasks.
#humans-and-machines 

Software is built from its source code. Does this mean that the source code tells everything there is to know over the lifecycle of the application? Sure, the source code tells a lot - and it has to. The source code describes how to build the software so that the compiler can do it. Clean code goes further, aiming to make knowledge as clear as possible for the other developers working on it. Still, code is often not enough. When code doesn't tell the full story, you need to add the missing knowledge to make it complete.

Most programming languages have no predefined way to declare the key decisions, to record the rationale, and to explain the choice made against the considered alternatives. Programming languages can never tell everything. they focus on their key paradigm and rely on other mechanisms to express the rest: naming, comments, libraries, and so on. 
#linguistics #social-constructs #sapir-whorf #architecture-decision-records 

Just as the Semantic Web aims to transform unstructured data into a web of data, a code base with annotations that clarify the semantics of the source code becomes a web of data that mahcines can interpret.
#transformation #language 

One of the most important pieces of information worth recording for future generations is the rationale behind each decision. What may seem like a stupid choice years later was not so stupid when it was decided. Most importantly, when the rationale is referring to a context at some point in time, and now the context is different, you are in a better position to reconsider the decision now.
#architecture-decision-records #decision-making 

Putting more knowledge into the code is not just for documentation; it can also help deliberately increase the skills of the teams working on it. Consider this opportunity when deciding on your augmented code strategy. When augmenting code, think about how your colleagues will react when they discover it.
#empathy #learning #design 

Even old projects with old technologies rely on conventions to communicate knowledge, describe their structure, and help with navigation.

Documentation by convention works only to the extent that everyone involved has enough discipline to adhere to the conventions consistently. The compiler does not care about your conventions and won't help much in enforcing them.
#social-contract #teamwork #discipline 

Thinking about intrinsic versus extrinsic knowledge has many benefits for design and for documentation.
#design 

Knowing all the reasons behind past decisions can enable you to more successfully make changes because you can either respect or reject each of those decisions deliberately.
#decision-making #architecture-decision-records 

In the book "97 Things Every Software Architect Should Know", Timothy High is quoted as saying: "As explained in the axiom 'Architectural Tradeoffs', the definition of a software architecture is all about choosing the right tradeoffs between various quality attributes, cost, time, and other factors." Replace the word 'architecture' with 'design', or even with 'code', and the sentence still holds.
There are trade-offs everywhere in software, whenever a decision is being made. If you believe you're not making any trade-off, it just means the trade-off is out of sight.
#consequences #decision-making 

"The Queen's speech is like the release notes for a minor new version of the UK!" Matt Russell, Twitter

When it comes to documentation, [developers] need to become our own curators, working on all the knowledge that is already there to turn it into something meaningful and useful. 
#curation-and-selection 

Unlike in art exhibitions, in software development what we need is more like a living exhibition with content that adjustts according o the latest changes. As the knowledge evolves over time, we need to automate the curation on the most imporant topics. 
Therefore: adopt the mindset of a curator to tell a meaningful story out of all the available knowledge in the source code and artifacts. Dont' select a fixed list of elements. Instead, rely on tags and other metadata in each artifact to dynamically select the cohesive subset of knowledge that is of interest for the long term. Augment the code when the necessary metadata is missing and add any missing pieces of knowlege when they are needed for the story.

On anything bigger than a toy application, extracting knowledge from the source artifacts immediately overflows our regular cognitive capabilities with too many details, and the knowledge becomes meaningless and therefore useless. the solution is to aggressively filter the signal from the noise for a particular communication intent. [...] "Too much information is as useless as no information." What would be noise from one perspective might be the signal from another perspective. For example, the method names are an unnecessary detail in an architecture diagram, but they might be important in a close-up diagram about how two classes interact, with one being an adapter to the other.
#meaningfulness #signal-vs-noise

Everything can be curated - code, configuration, tests, business behavior scenarios, datasets, tools, data, and so on. All the knowledge available can be considered as a huge corpus, accessible via automated means for analysis and curated extractions.
#curation-and-selection #audience #knowledge #data #parts-and-whole 

Provided that the content of the knowledge corpus is adequately tagged, it is possible to extract by curation out of it a business view of a glossary (that is, a living glossary), a technical view of the architecture (that is, a living diagram), and any other perspective you can imagine.

Basically, marking exemplars directly in the code enables you to then ask your IDE something like "What code is a good example of writing a REST resource?"
#sorting-and-searching 

The process of becoming familiar with a code base can be similar to the process of becoming familiar with a city. 
#architecture #cities 

Provide curated guides of a code base, each with a big theme. Augment the code with extra metadata about the guided tour or a sightseeing map, and set up an automated mechanism to publish as often as desired an updated guide from these metadata.

Consider your code base as a beautiful wilderness in the mountains where you go hiking. It is a protected area, and there are red-and-write hiking trail signs painted directly on the stones and on the trees. This paint does pollute the natural environment in a small way, but we all accept it because it's very useful and degrades the landscape only a limited amount.
#nature #compromise

An alternative to using strings in the guided tour annotations would be to use enums, which take care of naming, descriptions, and ordering at the same time. However, this moves the descriptions of each step of the guided tour from the annotated code to the enum class.

A guided tour is reminiscent of literate programming but in reverse: Instead of having 'prose with code', a guided tour has 'code with prose'.

The curator selects art works based on the chosen editorial focus. Most of the pieces available are left in the storage room, and only the few pieces of particular interest for the exhibit are on display. Similarly, documentation is a curation activity that involes deciding what's most important in a given perspective.
#curation-and-selection #art #empathy 

Documentation is a feedback mechanism that helps you notice when something is missing or wrong in the code or in the related knowledge.
#feedback #cybernetics 

For a successful living glossary, the code must be declarative. [...] A living glossary is also a feedback mechanism. If a glossary does not look good, or if you find it hard to make the glossary work, you know you have something to improve in the code. [...] A living glossary is not a goal in itself. It's above all a process that helps a team reflect on its code so it can improve its quality.
#product #feedback #quality 

Some problems are difficult to explain with words but are much easier to explain with a picture.
#non-verbal-communication 

Conversations and diagrams are not incompatible. Always being able to refer to the latest version of a diagram that reflects the current state of the software is a catalyzer of discussions.
#teamwork #non-verbal-communication #dialogue 

Living documentation makes you code, its design, and its architecture transparent for everyone to see. If you don't like what you see, you need to fix it in the source code.

The Agile Manifesto calls for "Working Software over Comprehensive Documentation". what is the working software itself were a kind of documentation?
#agile 

It is already quite common to design the user experience so that the users can have successful interactions wth an application without ever having to open the user manual. However, it's less common to design software so that its developers can understand it without having to even open the source code.
#design #user-experience #developer-experience

Anything that can answer a question can be considered documentation. If you can answer questions by using an application, then the application is part of the documentation.

Living documents are documents that are automatically generated using up-to-date knowledge from an authoritative source. In contrast, documents created using proprietary tools must be updated manually, which is tedious. Between these two extreme cases is refactorable documents, which must be manually updated but in a smart way, thanks to automation tools that reduce the labor-intensive burden.
(context - eg example of a tool that enables this is an IDE's Find and Replace)
[...] but the prominent example of a tool that enables refactorability is source code and the automated refactorings that apply on it. Developers spend a lot of time reading code and trying to get knowledge out of it. If you think of code specifically for its documentation value, then it becomes a key ingredient in your living documentation, an ingredient that embraces change very well.

Programming has always relied on conventions to convey additional meaning in the code. The programming language does a lot of the job. For example, in C# and Java, it's easy to recognize the method play() from the variable play because methods end in paretheses. But the parentheses are not enough to indicate the difference between class identifiers and variable identifiers. As a result, we rely on naming conventions, such as particular uses of lowercase and uppercase, to quickly distinguish between class names and variable names. Such conventions are so ubiquitous that they can be considered mandatory.
#consistency #social-constructs #patterns #linguistics #syntax #coding 

A convention is more than just a matter of convenience; it's also a social construct, a social contract between all developers in a community.
#social-contract #social-constructs #sapir-whorf #community 

Coding conventions try to extend the syntax of a programming language to support features and semantics that are missing.
#abstraction 

One of the most important documentation tools is naming. Despite its unattractiveness, naming should never be overlooked. More often than not, the names bestowed by the original authors are the only element of documentation available to retrieve those authors' knowledge. Good naming is immensely important. But good naming is difficult.
#naming #semantics #meaningfulness #spatio-temporal-relations 

Names don't live in isolation. In OOP languages, the set of class names form a language, and the words have various relationships to each other, gaining expressivity as a whole. 
#meaningfulness #linguistics #parts-and-whole #expression

Primitives are types, but types really shine when you use custom types instead of primitives. (see example on p225)
#expression 

A type is a perfect place to put documentation about a concept in a Javadoc section or its C# equivalent. Such documentation will evolve throughout the life of the type: It's created when the type is created, and if the type is deleted, its documentation will go away with it. If the type is renamed or moved, its documentation remains attached to it, so there is no maintenance.
#interdependence 

Comments can and often do lie. So does naming, though to a lesser extent. But types don't lie; if they did, the program would not even compile.
#lying #reliability 

One of the most obvious ways to make code more readable is to make it minic natural language, using a style that is called a fluent interface.
#communication #coding #language 

Using an internal domain-specific language (DSL) usually relies heavily on method chaining, among other tricks. A fluent interface is an example of an internal DSL that is built on the programming language itself. The advantage is that you get the power of expression without giving up all the good things around your programming language: compiler checking, autocompletion, automated refactoring features, and so on.

As in writing the first steps of writing tests in TDD, when implementing a fluent interface you start by dreaming. Write examples of using the ideal fluent interface by imagining it's there an perfect, even though you haven't started to build it yet. then take a subset of it and start to make it work. You'll encounter difficulties that will force you to reconsider alternative ways to express the same behavior.
#dreaming #imagination #creativity 

A colleague at Arolla, Mathieu Pauly, once tole me about the idea that meaning comes from the associations between things. Therefore, one way to learn what a class means is by looking at its relationships with all other classes that you already know.
#meaningfulness #semantics #discovery 

Requirements are more stable than design decisions. "If you can't change a decision, it's a requirement to you. If you can, it's your decision." - Alastair Cockburn, Twitter

Don't mix documentation of a strategy and documentation of its implementation. Make the strategy a pure evergreen document. Use another living documentation approach for the implementation, considering that the implementation will change more frequently.
#strategy #work #project-management

Naming is one of the most powerful means available to transfer knowledge.
#naming 

Knowledge is more valuable when it is connected, provided the connections are stable. Knowledge becomes more valuable when it is connected as a graph of relationships that conveys additional information and also brings structure.
#project-management #knowledge #value-and-worth 

All links need maintenance because the web is a living thing.
#conscientiousness #consciousness  #maintenance

One of the single most important pieces of knowledge everybody in a project should absolutely know is the vision of the project or of the product.
#product 

Don't hesitate to invest time and effort into learning stable knowledge. In particular, business domain knowledge and fundamentals of software architecture are evergreen content that are particuarly worth learning.
#growth #learning #pursuit-of-knowledge #investment 

Paying attention to how often pieces of knowledge change is a good strategy for reducing your workload over time because it means you can create documents that need to be manually updated only for knowledge that almost never changes.
#efficiency 

Written documentation is so often the default choice when it comes to documentation that the word 'documentation' has often come to be used to mean 'written document'. However, when we say we need documentation, we mean that there's a need for knowledge transfer for some people to some other people. The bad news is that not all media are created equal when it comes to the efficiency of transferring knowledge.
#documentation #meaningfulness #knowledge 

Newcomers superpower is to bring a fresh perspective. An astonishment report is a simple yet effective tool for learning both about should should be documented and what could be improved.

For a knowledge backlog, let each team member write on sticky notes the pieces of informations they'd like to have. Then have everyone put their notes on a wall and let them decide by consensus or by voting with dots what should be documented first.

A common approach is to spend time writing these decisions into a guideline or style book. the problem is that these decisions quickly add up to more pages than you expected, and a 12 page long document full of "you shall do this" and "you shall not do that" is far from an exciting read. As a consequence, most of these documents are like legal documents: They are so boring that most team members never read them - even once. They pretend to have read them on arrival, but in fact they hardly went further than the second or third page.
#regulation #quality 

Enforcing guidelines as automated rules or through access restrictions may express a lack of trust to the teams, but it depends a lot on your company culture. 

Traps should not be documented; instead, they should be refactored to be removed! Otherwise, the documentation will be a great case of a shameful comment.
#continuous-improvement 



