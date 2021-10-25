# ReadMe file for the application:
# | Percept PC - Unofficial Data Visualiser Application (PUDVA)


## What is this application and why was it developed
This application, called "Percept PC - Unofficial Data Visualiser Application", or in short "PUDVA" (or P.U.D.V.A.) is as it's name says a small, unofficial tool to view the data that the "Medtronic's Percept PC (B35200)" device generates.
Medtronic has it's own official tool, that comes with a mobile device and doctors could use it to analyze the recorded data, however as far as I know, there is no desktop support for that application.

Originally PUDVA has been created, because a friend of a friend of mine has the above mentioned device as a way of treatment, and he wanted to look at the data it generates, but did not know how the do that. As a solution, the predecessor of PUDVA ( a tiny, ugly concept app ) was made by me in early 2021. Later in that same year I rewrote the code completely into what PUDVA is today. The development was free-of-charge, out of will to help him, and possibly his doctors.

Because the application is already been developed, it would be a waste to not share it with others, including the public. The application is entirely free to download and use, and not in any condition you should pay for it. If you have any feedbacks or requests , feel free to contact me in the contact options that are in the application, or at github/twitter. You can find the applications license at the end of this document.


## How to download and make the application ready to use
1. Visit the only trusted source to download the app at: https://github.com/lazemiko/pudva
2. Here, above the ReadMe.md text you will see three files,  that are the followings:
  - README.md
  - ChangeLog.md (yet to come)
  - pudva_v0.7.1.20210911.1.zip

  Whichever "PUDVA" .zip file you find in here is the latest available, public version of the application. If you are interested in older versions, please use the contact options that are in the application, or at github/twitter.
3. Click on the name of the "PUDVA" file, with the left mouse button. ( That will load a new page. )
4. Here in this page click on the "download" button.
5. Upon downloading the file, extract it's content to a location where you want the application to run from.
6. To start the application, run the "main.exe" file that is located in the extracted folder.

## How to use the application
Upon launching the the application, on the left side vertical menubar, you will find a "Help" menu, which contains every information about the various features and the application.


## License
Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) - ( https://creativecommons.org/licenses/by-nc/4.0/legalcode )

Short, readable version of the license:
- You are free to:
  - Share — copy and redistribute the material in any medium or format
  - Adapt — remix, transform, and build upon the material
   The licensor cannot revoke these freedoms as long as you follow the license terms.


- Under the following terms:
  - Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
  - NonCommercial — You may not use the material for commercial purposes.
  - ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
  - No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

## Changelog
##### Version: v0.7.1.20211025.1
```
Release date: 2021.10.25
Changes:
- Text restructured on pages "Home" and "About"
- Added buttons for Notification page, "Copy to Clipboard" and "Export to file"
Hidden:
- Added modules of "markdown", "requests", and "tkhtmlview", all for the .md text display
- On Data page the date interval buttons now count from the topmost date
- LFP and Amp limits are added, and read from the file.
- On Data page the graph with the limit plots are more readable, a 5% buffer area was added.
- Added option to File page to convert normal data file to anonym version.
- Application packaging now happens in a separate environment dedicated to this process.
```
##### Version: v0.7.1.20210922.1
```
Release date: 2021.09.22
Changes:
- Code cleanup and optimisation.
- Events are properly shown now (EventLog was missing competly, other events appeared incorrectly)
- "Unload File" button was added to clear the currently loaded data
- "Notification" page now records more runtime information ( both detailed error messages, and notifications )
- Application was renamed to "PUDVA" as of ( PerceptPC Unofficial Data Visualizer Application )
- Application is now available on the "github.com" website for download at:
https://github.com/lazemiko/pudva
```
##### Version: v0.7.0.20210902.1
```
Release date: 2021.09.02
Changes:
- Initial release of this 'preview' version.
```
