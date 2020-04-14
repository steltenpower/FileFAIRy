# dataCentricFileExplorer
When you've read the data-centric manifesto, or know about linked/FAIR data, you know data is your asset and depending the task you pick a different application to work on it.
However, many people work in applications, never thinking about data types, up to the moment they call you for help on something that was supposed to be done yesterday and you tell them they've run into vendor lock-in. One of the reasons they 'think in' applications might be that in Windows file explorer the files don't have icons for filetype, but icons for the associated applications.
This idea is about changing that. A very nice extra feature would be a context-menu list of supporting applications (installed local and open source available on-line). Another extra feature would be to allow validating-on-save, to detect non-valid files.

Some directions for implementation:
- On installing this takeover all filetype associations
- Other extensions to Windows File Explorer do exist (This is not necessarily a Windows-only idea, but that is where the problem needs solving the most)

update: I need to look into https://fileviewerplus.com/manual/overview

extra: if you also have webaccess to some of the same drives/folders/files you can set the relation path/URL in the settings, which then activates the possibility to "copy shareable URL".
