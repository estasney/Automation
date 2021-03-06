# Lazy VE Extraction

![Mr.Robot](https://thumb.ibb.co/ejYLt5/Logomakr_6b4xoc.png)

Lazy VE Extraction automates the tedious process of downloading multiple Excel files from VE. 

### *Set it and forget it!*



## Installation

#### Adding Selenium IDE

 1. Install [Selenium IDE](https://addons.mozilla.org/en-US/firefox/addon/selenium-ide/) for Firefox
 2. Once installed, click *Open Menu* and then *Customize*. Drag Selenium IDE over for quick access.
 
#### Change how Firefox Handles Downloads
1. In Firefox, navigate to Options. Or copy-paste this into your address bar
`about:preferences`
2. Click *Applications*
3. For *Microsoft Excel 97-2003 Worksheet*, set the action to *Save File*

#### Download Script Files
1. Download the Scripts from [GitHub](https://github.com/estasney/LazyVE/archive/master.zip)
1. Open the download folder, right click on *Automation-master* and click *Extract All*
1. Pick a folder to extract it to. Remember it, we'll need it later.

#### Load the Script Files

## Configuration

#### Configure Options
1. Open Selenium IDE from Firefox
2. Click *Options* :arrow_right: *Options* 
3. On the General Tab, find *Selenium Core extensions (user-extensions.js)* and click *Browse...*
4. Find the folder where you extracted the ZIP file. Locate the file *sideflow* or *sideflow.js* and click *Open*
5. Next, un-check *Start recording immediately on open*
6. Click *OK*

#### Load the Script
1. Click *File* :arrow_right: *Open*
2. In the same folder, locate Lazy VE 0.5.1 Note: The numbers may be different. This simply indicates the version number.
3. Select Lazy VE and Click *open*

## Running the Script

#### Begin
1. Navigate to VE

##### Note
1. Ensure VE is set to *Professional* Mode, not *High Volume*. Hover over *Products*. If you see *High Volume* as an option, this is set correctly.
2. Ensure you do not have any *Custom Search Settings* saved. Check this by Opening *Preferences* :arrow_right: *Custom Search Settings*. If you do, click *Clear Selections* and click *Save*

#### Start the Search
1. Start a new search by clicking *Candidates* :arrow_right: *New Search*

#### Start the Script
1. You may now start the script by clicking either of the green *Play* buttons.
2. You may also start the script after running your search.



