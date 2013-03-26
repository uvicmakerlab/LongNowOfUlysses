#"The Longer Now of Ulysses: Digital Life After Analog Death"

##Draft Components

As before, My raw components (if you want to look at the code) can be found on my personal repo here: https://github.com/resurgam/Log/tree/master/LongNowEncoding/extracts

otherwise, the mostly-complete site is viewable here: http://web.uvic.ca/~dcarlton/extracts/complete/longernowsite/
Keep in mind that it works best on Firefox. *Please use Firefox if you are able*. Seriously. It will run in other browsers, but has a number of aesthetic quirks unique to each platform. For instance, Internet Explorer can't understand my custom font, Opera and Chrome have issues with italics and indenting, while Safari has issues only with italics (though this throws off the line justification a little). None of the problems are site-breaking, but they do ruin the aesthetic presentation a little. Unfortunately, they are browser issues, and as such, are not something that I can feasibly do much about. 

Basically, the site, as promised, consists of a basic homepage with a small (albeit incomplete) description of the project, and the 18 extracts, along with a link to the UVic Library website to aknowledge their support. Hopefully I'll be able to expand my site's description, and connect with the rest of the projects at a late date with another side-bar, or something similar, since I have a great deal of empty space to work with.  The site's not beautiful, but it works!

##Workflow (plus new additions)
 
*While there are a few screenshots of the very early stages of my project in my repository, I feel that a more detailed textual description of my process will tell you more than pictures ever could.*

After transcribing all 18 texts by hand, and producing my schema, I was ready to start the actual project.

1. First, I copied over the files from my Aldhelm XML project into a new folder called "extracts" to use as a "skeleton" for this project, and then proceeded to cut away all the bits that I knew were superfluous, as well as implement and test my custom TEI schema.  

Next, I copied over the .png scan and .doc transcription of the "Penelope" extract (chosen for its simplicity), and copy/pasted each line manually into my XML "frame". I then moved everything into a folder called "Penelope". From here, I was able to start working on my CSS to test and decide upon different font sizes, line orientations, spacing, etc.  

Once I had completed a working, web-readable version of "Penelope," I wrote a small program in Java to count the numbers of vowels, consonants and other characters in a text string, in order to record and mark-up this information in my XML documents. Penelope was, of course, the first text to be plugged into the program. I discovered that it has 494 vowels, and 807 consonants, and inserted this information into my XML accordingly. After implementing a nice paper background in CSS, Penelope was basically done. 

2. Over the next few weeks, I proceeded to mark up the remaining 17 of my texts on a very basic level, in order to at least make them web-readable, if not formatted to look they way they ought to. I basically followed the same process I used for Penelope for each extract, by tagging paragraph numbers, line types, etc. in the XML, using my Java program to find out the number of vowels and consonants, altering the CSS accordingly, and then testing everything in a number of browsers. 

3. Over the last week I went in to nine of the extracts (batch 1) and worked on the CSS, in order to express more detailed visual elements like italics, headers, font-weights, and line-breaks. This stage has been especially difficult and rewarding for a number of technical reasons, but I now have a process to work from. Basically, I test out a new technique in one extract (such as using a lb tag in my XML, and then a lb{text-indent:50px;} expression in CSS to render a paragraph indent), and then copy and paste what works into my next extract, while discarding those things that either don't work, or become progressively less necessary as my script becomes less clunky. I've now written enough code that I can pick-and-chose what I need for almost any scenario, without having to make anything truly "new".  

4. I copied the above process to mark-up and express the remaining 9 extracts, and then began to work on implementing a white-space fix a little more fervently.

5. I disocvered that using the white-space: pre; tag in CSS *does* work, but requires me to *not* use per-pixel indent commands alongside it. As soon as I shuffled stuff around, it worked! Yatta! The first finished text was Penelope. I adjusted font-size to suit the new formatting, too.

6. I went through and implemented the above white-space fix to the remaing 17 extracts, some of which required extensive reworking. This took a really long time.

7. Created my homepage using a combination of DreamWeaver and hand-coded per-pixel positioning for my elements (done in Notepad++, mostly). This was tedious, but gave me the basic result I was after. I then made sure all my extracts were in the appropriate directories, etc, so that my script was pointing to the correct location.

8. I did my front-page write-up, mostly based on my needs-assessment assignment from earlier in the term.

9. All tentative deliverables completed on time, March 25, 2013.


