#"The Longer Now of Ulysses: Digital Life After Analog Death"

##Draft Components

My draft components can be found on my personal repo here: https://github.com/resurgam/Log/tree/master/LongNowEncoding/extracts

or live online here: http://web.uvic.ca/~dcarlton/extracts/complete/

Currently, there are 9 out of 18 extract fully marked up (except for line justification). The other 9 are web-readable, but are not yet formatted to visually reflect line-breaks, italics, etc.

##Workflow

*While there are a few screenshots of the very early stages of my project in my repository, I feel that a more detailed textual description of my process will tell you more than pictures ever could.*

After transcribing all 18 texts by hand, and producing my schema, I was ready to start the actual project.

1. First, I copied over the files from my Aldhelm XML project into a new folder called "extracts" to use as a "skeleton" for this project, and then proceeded to cut away all the bits that I knew were superfluous, as well as implement and test my custom TEI schema.  

Next, I copied over the .png scan and .doc transcription of the "Penelope" extract (chosen for its simplicity), and copy/pasted each line manually into my XML "frame". I then moved everything into a folder called "Penelope". From here, I was able to start working on my CSS to test and decide upon different font sizes, line orientations, spacing, etc.  

Once I had completed a working, web-readable version of "Penelope," I wrote a small program in Java to count the numbers of vowels, consonants and other characters in a text string, in order to record and mark-up this information in my XML documents. Penelope was, of course, the first text to be plugged into the program. I discovered that it has 494 vowels, and 807 consonants, and inserted this information into my XML accordingly. After implementing a nice paper background in CSS, Penelope was basically done. 

2. Over the next few weeks, I proceeded to mark up the remaining 17 of my texts on a very basic level, in order to at least make them web-readable, if not formatted to look they way they ought to. I basically followed the same process I used for Penelope for each extract, by tagging paragraph numbers, line types, etc. in the XML, using my Java program to find out the number of vowels and consonants, altering the CSS accordingly, and then testing everything in a number of browsers. 

3. Over the last week I went in to nine of the extracts (batch 1) and worked on the CSS, in order to express more detailed visual elements like italics, headers, font-weights, and line-breaks. This stage has been especially difficult and rewarding for a number of technical reasons, but I now have a process to work from. Basically, I test out a new technique in one extract (such as using a <lb> tag in my XML, and then a lb{text-indent:50px;} expression in CSS to render a paragraph indent), and then copy and paste what works into my next extract, while discarding those things that either don't work, or become progressively less necessary as my script becomes less clunky. I've now written enough code that I can pick-and-chose what I need for almost any scenario, without having to make anything truly "new".  

##Problems and Surprises

1. Despite everything I try, I can't render blank space using XML or CSS. If I am to justify the lines as they appear in the book, I will need to fix this.

2. I was surprised by how easy it was to find a font that approximated the book-font used in the images.

3. to that end, I was equally as surprised to discover that said font renders a bit differently depending on the browser/medium in which it is being used. Thus, while my .doc transcriptions look nearly perfect (except for the lower-case "w"s), my XML files are not quite as aesthetically accurate.


##Questions

1. Is there any particular way you would like each extract mapped together? I was planning on making a simple home-page with static links to each of the 18 texts, but am open to suggestions.

2. Are there any particular textual/aesthetic features of the extracts you would like to see marked up?

3. Does anyone know how to preserve white space in an online document using CSS, XML, or any other portable web technology? This would be a huge help to me.


