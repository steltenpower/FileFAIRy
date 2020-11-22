# dataCentricFileExploring
As I too often heard "What do you mean with file type? I just use application X" and then having to tell someone what they now immediately want is impossible for (vendor) lock-in reasons, I imagined part of that could be prevented by changing how they view lists of files outside this application:

Lists of files appear in many places: Windows file explorer, or one of the many 'webdrive' options that are either rather generic (local network drive, Teams, NextCloud, Dropbox) or specific to research: Figshare, Dataverse, DANS EASY and Surf Research Drive. What I think these user interfaces could use for every file:
- icons for file types, not for the associated application
- always show the extension as part of the filename (in Windows File Explorer a setting that is now off by default I think)
- context-menu list of supporting applications (installed on machine, available within school, national facility, or open source on the web)
- validating for unambiguity (is it a valid .html file? Does the data adhere to the schema? etc.)
- other quality checkers (spelling, bugs, speed, contrast, etc., etc.)
- converters (especially closed to open file type)
- highlight preferred file types (for example for archiving reasons) and have a link to click
- file type dependent help option (local support, open communities, etc.)

On Windows File Explorer it could be realized by:
- create something that when installed takes over all file type associations
- maybe extending it. On previous Windows versions I've seen that done. Then you could also maybe in the contextMenu have "link to file in web interface". Maybe learn from https://fileviewerplus.com/manual/overview

Where to try to get information about file types:
- wikidata
- others

See also:
- https://www.wikidata.org/wiki/Q235557
- http://loc.gov/preservation/digital/formats/fdd/browse_list.shtml
- https://dans.knaw.nl/en/about/services/easy/information-about-depositing-data/before-depositing/file-formats
- https://www.wikidata.org/wiki/Property:P3381
- https://www.wikidata.org/wiki/Q686498
- https://www.wikidata.org/wiki/Q3570403
- https://www.wikidata.org/wiki/Q935809
- ftype assoc
- https://docs.microsoft.com/en-us/windows/win32/shell/how-to-assign-a-custom-icon-to-a-file-type

 (possible companion of [webber](https://github.com/steltenpower/webber))
