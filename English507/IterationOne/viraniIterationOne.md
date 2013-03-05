#Iteration one of **Demisemiquavers: The Long Notes of Ulysses**


# Workflow of the Audio Repo #

## Gathering The Audio ##

1. The first step here is the critical determination of source audio. By this, I am referring to:

 1.1)  The choices made in deciding what moments in the text call out to sound. These moments range from the mention of an opera, the transcription of a character singing a song, or the description of auditory experience (footfalls, for example). 

 1.2)   The research and or discovery of films, musicians, composers, or anyone else who have created audio *after-the-fact*. This encompasses remediations, tributes, and inspirations. Wikepedia, fan pages, and scholarly articles and reviews are all sources for discovering this information. 

2.  To lead off from 1.2: I discover the film "Bloom" from 2003, a film remediation of Ulysses. Learning that David Kahne composed an entirely original soundtrack for the film, I discover that there are 18 audio tracks available. This is done by a simple internet search. (The soundtrack for this film will constitute my "Case Study" for the purposes of this workflow demonstration and draft components exhibition. I choose this source for the workflow because it has provided the most obstacles, and allows me to cover audio grabbing from a browser, copyright law, and a host of extra fun). 
![](http://ulysses.ie/wp-content/uploads/2011/10/banner1.jpg)

3.  Navigating the rights of the audio is the next step. While there are conventional rules of copyright and fair use, investigating each composer, company, and publisher's specified copyright is necessary. 

  3.1) the [U.S. Copyright Database](http://www.copyright.gov/records/) provides publicly available records of copyright for specific clients, companies, and publications of America.

 3.2) the [Canadian Intellectual Properties Office](http://www.cipo.ic.gc.ca/eic/site/cipointernet-internetopic.nsf/eng/h_wr00003.html) provides our country's overview laws and fair use determinations based on medium. 

 3.3) since *Bloom* is an Irish film with American contributors, I felt it was necessary to investigate the specific international copyrights that the company no likely put in place for the soundtrack, outside of North American standards of fair use and piracy. In this case, this required investigating the legal tabs of [the film's web presence](http://ulysses.ie), which brought me to the [Bloom University Collection](http://ulysses.ie/bloom-university-collection/). Based on a combination of copyright law and the company's own specifications, I learn that I am unable to reproduce the full audio for any purposes without the licensing available in this package. The internet being our friend, however, gives us options. 

##### The Legal Ripping of Audio #####

By Fair-Use standards, small portions of audio files are publicly available as samples. In this case, the Amazon linking to the soundtrack of the film provides 26-second clips of each of the 18 tracks for distribution and preview. 

How do we apply this equivalent of an iTunes preview to the audio repo?
Luckily, Google has an app for this. Well, an extension, really. 

The Google Chrome extension [Flash Video Downloader](https://chrome.google.com/webstore/detail/fvd-video-downloader/lfmhcpmkbdkbgbmkjoiopeeegenkdikp?hl=en) provides a small blue arrow at the right end of the chrome toolbar. As can be seen in the image below, whenever a downloadable form of media (video or audio) is available on a page, this extension notifies you and provides the available formats and download size.

![](http://i.imgur.com/awQTYY8.gif)

Now, the loophole here is simple. By appropriating these sample audio files, I am staying within reasonable fair-use of audio, as is Amazon. Technically, our purposes are just further promotions and previews.

## Storing The Audio 

1. **Formatting**: Ideally, all the audio files would be [.wav](http://en.wikipedia.org/wiki/WAV) or [.flac](http://en.wikipedia.org/wiki/FLAC) files, so that they can retain lossless quality, being uncompressed. Availability and size restraints, as well as general interoperability dictate that the files must be mp3, however. Most of the files (whether they were purchased, downloaded, ripped, or linked) are standard as mp3's. Those few and far between that have been .flac, however, have been run through a simple [audio converter](http://www.online-convert.com/).

2. **Interoperability**: This repo essentially aims to serve two functions, it will be a source of data for study, and a source of data for use. In terms of use, two other projects for the LongNowOfUlysses exhibit will be using the actual audio files as part of their presentation and physical exhibition. 

 2.1) Mitch Renaud's Max/MSP Rig: In addition to his own sounds, Mitch will be using some of the audio samples from this repo in his controlled use of sound for the exhibit space. Rather than some awkward attempt at live hosting during the exhibit, this has amounted to a simple sharing of media. After they are processed, the audio files are placed in a [DropBox](https://www.dropbox.com/) folder shared between Mitch and myself, for him to use at his discretion.
![](http://i.imgur.com/MtJ5vSt.gif)
 2.2) Laura Dosky's TimeLine: For the physical exhibit, Laura and myself will be collaborating, likely involving a TimeLine display with audio callouts. This will be accomplished by linking the metadata of the audio from the Google Spreadsheet in Dublin Core to Laura's work.

## Documenting and Archiving ##

Standard archival practice for audio is to commit the metadata to Dublin Core format. For the purposes of the exhibit, this has been done through Google Spreadsheets for ease-of-access. As referenced in my [Data Model](https://github.com/uvicmakerlab/LongNowOfUlysses/blob/master/English507/DataModel/ViraniDataModel.md), the terms are drawn from [Dublin Core](http://dublincore.org/documents/usageguide/elements.shtml), used by the majority of archival projects and libraries for audio archiving. Once applied to the spreadsheet, the DC metadata for some of the tracks from *Bloom* look like this:
 ![](http://i.imgur.com/phagLWR.gif)
.

######Secondary Coverage ######
The only deviation from standard DC terms is the element "Secondary Coverage." I have made the critical choice of included two sets of geo's, listing as "Coverage" and "Secondary Coverage," to encompass both the referential and actual locations pertaining to the audio files. The referential location would be the corresponding place in the text of Ulysses, and it's geo-coordinates. The actual location would be the location of the audio file's creation. (for Nighttown, the difference would be the nighttown location in Dublin, and the Oddyssey studio in Dublin). 

The DC and Google Spreadsheet allows for one additional stream of interoperability: David's xml documentation. Using [Pamela Fox](http://blog.pamelafox.org/2009/05/how-to-convert-google-spreadsheet-into.html)'s xml gadget for Google Spreadsheets, I can export the DC Metadata as a valid xml file, in which each DC term becomes an XML element. 

(Note: this export method for GS-XML has proved spotty, so a backup method is to install the [Microsoft Plugin to convert EXCEL to XML](http://www.youtube.com/watch?v=1OKZN2sUuvs)) 


####The draft components are as follows:

1. A publicly available [DropBox folder](https://www.dropbox.com/sh/01rtkhlf7jw3yvb/A4ftOaamD1?m) housing the audio, with the ability to transfer for further storage and use.
2. A [Google Spreadsheet of the audio metadata in Dublin Core](https://docs.google.com/spreadsheet/ccc?key=0AmC4guPyb1GedHB0NnBGQmZUbkVxczJ1X1lOTHdfMlE&usp=sharing), complete with relevant data for multiple mapping and audio related projects.


####Questions for the group:

1. In an attempt to justify my selections (and out of a necessity to limit the content), I am working on a statement that places an emphasis on *spread*. By this, I mean that I aim to cover only the remediations that reached a wide audience (such as *Bloom*), call-outs from the text to popular songs (such as *The Croppy Boy*, which is a well-known Irish song mentioned in Ulysses multiple times), or the "blatantly-everywhere," such as the sounds of footfalls, oceans, bars, and glass that appear throughout the novel. My question: Would this require a high level of justification? Would a visualization from Voyant be necessary, perhaps to show the frequency of mentions dictating choice?

2. Do the interoperable features of this archive seem relevant? These are many of your projects that I will be linking to, so this is important.

3. Is the dual geo-tagging of coverages necessary? I find it cool, personally. 


####Surprises:


I knew copyright was a harsh mistress, but damn. I had assumed that scholarly endeavours would get some leighway. I was wrong. (I would have added on "dead wrong,"  but Bruce Willis and Charles Bronson share a copyright on it). 

It may seem foolish and naive, but I was honestly a bit shocked to find out that archiving audio required metadata beyond the standard Id3 tag. When I conceived this project, I had a much smaller scope of metadata in mind!

The amount of files that are available in .flac and not .mp3 is ridiculous. For as moderately un-useable and large as .flac files are, I would have assumed an mp3 or .wav standard. This has lead to a lot of tedious conversion work that I wasn't expecting. But hey, everything can't be lossless all the time! 
