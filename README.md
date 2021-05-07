# FAIRfilesViewing
First think of any list of files, e.g. Windows File Explorer, or what you get in DropBox, Google Drive, Microsoft Teams, OwnCloud, NextCloud, Figshare, Dataverse, DANS EASY, SURF research drive and many, many more.
Now look at the quick sketch here and below I'll explain how and why they differ.
![alt text](https://repository-images.githubusercontent.com/149428210/f8bcf200-77cf-11eb-93f8-452cf9db3dcb "Sharing a network of data, over the list of files you have")

DESIGN: The columns from left to right:
=======================================
- OPEN SPEC: Is the file type of a file a so-called open specification? I used a green O for open (e.g. HTML), a dashed O for 'open' (e.g. OOXML, open by license, but seems not designed to make interoperability easy) and a red C for closed formats.
- PREF: Is it a preferred/allowed format by parties (journals, research archives, anybody) you find important? I used the direction and color of thumbs to visualize. Clicking it pops up settings for (more) validation: spelling, linters, accessibility (a11y), link checkers, etc., etc.
- VALID: What's the result of automatic validation of the file against the specification and schema? See goodtables.io, validator.w3.org and others.
- ICON: for file types, not for the associated application. To help data-centric thinking of datacentricmanifesto.org, especially now filename extensions are often hidden by default nowadays. Clicking it pops up specific help options (colleagues supporting, open communities, convertors, etc.) This part was inspired by a researcher saying "What do you mean with file type? I use app X." He was really disappointed when I had to explain him vendor lock-in.
- NAME: clicking it pops up all adresses, with protocols (DOI/HTTPS/webDAV/etc), this fileviewer is aware of that the file can be reached. Not drawn yet, to be added: a left arrow that reveals something about what links here and a right arrow for what this links to. Arrows are faded if there's nothing to reveal.
- CONTEXT-menu (on the name): list of supporting applications (installed on machine, available as webapp, in institute appstore, or open source on the web)
- USERS: files are usually shared over teams, roles, institutes, and our digital assistents. Who's in control, or who's it shared with and how?
- DATE:
- SIZE:
- COMMITED: everything has a commit/version. We all GIT, right?
- (not in drawing yet): MORE METADATA (DC and other vocabulaires) and based on all of the above:
- (not in drawing yet): RELATED/SUGGESTIONS: Find related stuff and people to cooperate with (or compete against?).
<br>
<br>
<br>

ON IMPLEMENTATION:
==================
Where to try to get information about file types:
- wikidata
- https://www.wikidata.org/wiki/Q235557
- https://www.wikidata.org/wiki/Property:P3381
- https://www.wikidata.org/wiki/Q686498
- https://www.wikidata.org/wiki/Q3570403
- https://www.wikidata.org/wiki/Q935809
- http://loc.gov/preservation/digital/formats/fdd/browse_list.shtml
- https://dans.knaw.nl/en/about/services/easy/information-about-depositing-data/before-depositing/file-formats

On Windows File Explorer it could be realized by:
- create something that when installed takes over all file type associations
- maybe extending it. On previous Windows versions I've seen that done. Maybe learn from https://fileviewerplus.com/manual/overview
- ftype assoc
- https://docs.microsoft.com/en-us/windows/win32/shell/how-to-assign-a-custom-icon-to-a-file-type
- https://hello.fileslide.io/

<br>
<br>
<br>
 possible companion of [webber](https://github.com/steltenpower/webber)
 
