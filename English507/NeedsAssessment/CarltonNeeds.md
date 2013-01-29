## Needs Assessment Assignment

# The Longer Now of Ulysses: Digital Life after Analog Death
### By David Carlton

## Description
Because the sections selected for our exhibit have been bereft of their original literary context, and inserted into a new algorithmic one, they have taken on a fundamentally new form that ought to be studied as a  unique “text”, representative specifically of the “Long now of Ulysses.” To this end, I will present each extract as a separate web-page connected to a main hub, and use XML to mark-up each piece according to pre-defined parameters, such as paragraph structure, vowel density, and word-type. Abstractions like *vowel density* will help map the aesthetic appearance and "sound" of the text within the XML code, and are thus important for the purpose of representing the *whole* text—in both appearance and form—on a more quantitative level. Creating a website for our Ulysses extracts is also useful for a number of more pragmatic reasons. For instance, its web presence will exist long past the “death” of its physical exhibition, and thus remind the observer how the “Long Now of Ulysses” was crafted around—and beyond—its “new” algorithmic text, and how he or she might recreate the exhibit at this fundamental level. Further, by rendering our extracts as simple web-pages—wherein the XML code is invisible to the user—the textual backbone of the exhibit can be readily interrogated in a more abstract way, while still remaining eminently accessible to the general public.  

## List of Resources 
Before anything else can be accomplished, my project will require me to acquire and analyze the scanned images of the algorithmically selected excerpts from *Ulysses*. I will then use XML (written within the oXygen scripting environment) to mark up the texts according to the parameters defined in the project's RNG schema, CSS to express my XML files in a web-readable format, and Mozilla Firefox, Opera, Google Chrome and Internet Explorer to gauge how well my marked-up texts render in each browser, and alter the scripts as necessary.  

Similar to the [XML edition of the Anglo-Saxon Chronicle](http://asc.jebbo.co.uk/), I will use a simple HTML environment as a hub for my XML excerpts. However, unlike the AS Chronicle, which has used XSLT to translate its XML into XHTML, I will use CSS to render the marked-up files. This will make the raw markup code more easily available to all interested parties, and ultimately allow the project to be more streamlined from inception to completion. Also, unlike the AS Chronicle, I will express my encodings in a close approximation of the same font and orientation as the scans, so as to preserve the aesthetic flavor of the static images, while also providing the flexibility of digital text. To accomplish this, I will first analyze the scanned excerpts, the original book from which the excerpts derive, and any secondary typographical information that is available. I will then choose the necessary typeface and implement it accordingly. I have had success with a similar XML/CSS experiment, centred around the macaronic Old English poem, Aldhelm, in which I have manually rendered the poem in a close approximation of tenth-century English Insular script using CSS and a custom font. The result can be found at my own [Uvic Web-Space](http://web.uvic.ca/~dcarlton/Aldhelm.xml). Although the XML in this page is only partially marked up, and the CSS is rife with incomplete interactivity components, I will doubtlessly recycle much of the code and design from this project for my “Long Now of Ulysses” contribution.  

Using oXygen, I will mark-up the dates and times of the exhibit, the names of those involved, the bibliographical information of the original book from which the extracts have been taken, and a number of other prose-text related particulars, such as paragraph size, font, number of nouns/verbs/adjectives/vowels, etc.) to give an overall "literary-aesthetic frame" of each extract as a textual object that's representative of the exhibit.  

## Scope and Constraints
Since I only have three months to complete my project, I will be unable to create a visually exciting, or interactive web-space. I will also be unable to create my own schema from scratch. Such a task would require a greater knowledge of the pertinent technologies than I currently possess, as well as a greater allotment of time. Since I will have to be selective about what I will mark-up in XML, I will focus on the aesthetic and structural elements of the text, such as vowel density/paragraph breaks, and treat parts of speech as a secondary addition. Due to my lack of design experience, my index page might pose the greatest issue from a presentation standpoint, and may be subject to subsequent reassessment. I am also concerned with discovering a suitable font for my transcriptions, but I'm sure I will discover something. Unfortunately, my other graduate responsibilities, such as my paid RA work, will inevitably censor the amount of time I am able to devote to the project. Of course, such obstacles will be overcome, but they are still problematic.  

## Deliverables
My project will deliver a web site comprised of one main HTML hub, which will link to seventeen XML pages (expressed through CSS), each containing the text of one excerpt. Each XML excerpt will be typographically styled after the typeface and page-layout of its respective scanned image, and marked up (behind the scenes) according to sentence structure, paragraph breaks, vowel and consonant density, and the frequency of each word type (noun, verb, etc.).  

## Benefit 
My project will benefit the general public by providing an easy-to-use platform on which to view the “Long Now of Ulysses” long after the physical exhibit has been taken down, and also a place to “experience” the exhibit at home, even during the exhibit's run. Additionally, the global nature of online media means that the exhibit can—at least at textual level—be experienced by individuals and groups who would be otherwise unable to, because of physical borders. It will also benefit interested academics by providing a marked-up version of our textual extracts, which will facilitate a variety of more abstract, quantitative studies that would be otherwise impeded by the simplicity/ of “regular” text. Of course, those who do not wish to delve into the computational aspects of the extracts need only to avoid interacting with the back-end XML tags; since they will not be expressed in the browser-readable text, once must purposefully view the source-code of each page to access them.  

## Deadlines and Milestones
Alongside the following dates I expect to keep a running log of my progress, and any glitches I run into along the way.

###My Deadlines:
1.  __February 5th__ Have the font information acquired, and the schema defined and started 
2.  __February 12th__ Have first half of texts transcribed; have font downloaded and ready 
3.  BEFORE READING BREAK, HAVE SCHEMA READY TO GO
4. __February 26th__ Have all texts transcribed and ready to be marked up; start marking up texts 
5. __March 11th__ Have first half of texts marked up and edited; start second half 
6. __March 18th__ Have second half of texts marked up; have homepage planned out 
7. __March 25th__ Have homepage completed; everything is pretty much done now 
8. __April 2__ Final presentation; have everything fully presentable at this point; start writing report 
9. __April 16__ Have final project report and all materials handed in to Jentery by this date  

## Support
More than anything, I will need help customizing a schema (RNG) for my purposes, or locating one that already includes the components outlined in this document. I will also need help creating a somewhat attractive hub for my encoded texts, and would appreciate software recommendations, or workshops on how to do this. I have used Dreamweaver in the (distant) past to author HTML documents, but am unsure if this would be the most expedient option, or if something else would serve me better.  

## Project Goals
For my project to be successful, it needs to accomplish two simple things:
1.) Each extract should be available in XML format, expressed via CSS and linked together by a main-page (this main-page will contain basic information regarding the exhibition as a whole, and the prerogative behind its XML renderings).
2.) All texts should be easily readable by any lay person, and rich enough in mark-up to be useful for interested academics.  

## Personal Goals
I plan to accomplish the following two things by end of term:
1.) Having used web technologies in only a limited capacity for DH purposes, I would like to learn more about TEI, schemas, and the overall flexibility of XML, and other related technologies as they apply to the academy. 
2.) I hope to become more proficient in design, and want to learn more about fonts and type-faces. This relates to my passion for books as physical objects, as well as my plan to express my encoded documents using the same type-face as the edition they were taken from, or at least a close approximate.  
