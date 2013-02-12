# David Carlton Log February 11, 2013

This entry will serve as a brief log of what I've done, and a short description of what my schema will be 

able to do.

## What I've done

1. I transcribed all 18 texts by hand, and settled upon Adobe Caslon Pro as my base-font. A few letter 

forms don't match up (most notably lowercase "w"), but I should be able to do some find-and-replace voodo 

with CSS to replace said Caslon "w"s with Times New Roman ones. This will happen later, of course.

2. I settled upon what I want in my schema, and generally how I'm going to mark up the texts

3. I created my schema using Roma and a modified TEI-lite framework


## What my schema is, and what it will do

First off, my schema can be found under the "dataModel" folder titled "carltonDataModel.rng", and the 

transcribed texts can be found under the "Log" folder on my account (Resurgam)

Among the standard TEI modules/elements/attributes for characters, word types, lines, paragraphs, and 

various descriptors for bilbiographical purposes, my schema imcludes the following custom elements:

1. a "vowels" attribute under the "text" element, which takes a numerical value >-1
2. a "consonants" attribute under the "text" element, which takes a numerical value >-1
3. a "fontStyle" attribute under the "lg" element that takes a text description of "normal", "large", "bold", "italic"  
4. Numerous other little tweaks 


I left a number of tags in my schema, which I likely won't use. However, it's good to have them in there, 

should the need arise.  
