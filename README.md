# dataCentricFileExplorer (companion of [webber](https://github.com/steltenpower/webber))
When you've read the data-centric manifesto, or know about linked/FAIR data, you know data is your asset and depending the task you pick a different application to work on it.
However, many people work in applications, never thinking about data types, up to the moment they call you for help on something that was supposed to be done yesterday and you tell them they've run into vendor lock-in. One of the reasons they 'think in' applications might be that in Windows file explorer the files don't have icons for filetype, but icons for the associated applications.
This idea is about changing that. A very nice extra feature would be a context-menu list of supporting applications (installed local and open source available on-line). Another extra feature would be to allow validating-on-save, to detect non-valid files.

Some directions for implementation:
- On installing this takeover all filetype associations
- Other extensions to Windows File Explorer do exist (This is not necessarily a Windows-only idea, but that is where the problem needs solving the most)

update: I need to look into https://fileviewerplus.com/manual/overview

extra: if you also have webaccess to some of the same drives/folders/files you can set the relation path/URL in the settings, which then activates the possibility to "copy shareable URL".

Per filetype maybe wikidata can deliver an icon, description and list of programs that can work with it in a (specified) way. Work to do at https://www.wikidata.org/wiki/Q235557
(also see
http://loc.gov/preservation/digital/formats/fdd/browse_list.shtml
https://dans.knaw.nl/en/about/services/easy/information-about-depositing-data/before-depositing/file-formats
https://www.wikidata.org/wiki/Property:P3381
https://www.wikidata.org/wiki/Q686498
https://www.wikidata.org/wiki/Q3570403
https://www.wikidata.org/wiki/Q935809
ftype
assoc
https://docs.microsoft.com/en-us/windows/win32/shell/how-to-assign-a-custom-icon-to-a-file-type
)

Of course list files this way by default in web drives
