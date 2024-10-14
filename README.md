# Create DMG file from *.app file 

1. Open disc utility and create partition 
    
    Select: File > New Image > Blanck Image 

    Adjust: 
    Save As: app_name_draft
    Name: My App
    Size (*.app <= size) 
    Format: Mac OS Extanded (Journaled)
    Partitions: Single Partition - GUID Partition Map
    Image format: read/write disc image  

Navigate to /Volimes/My\ App and create .background folder.

Copy *.png or *.jpg file to the .backfround folder on the disc.


2. Create alias to /Applications 

    Go to / directory in finder

    Right click on Applications folder > Make Alias 

    Alias will be created on the Desktop 


3. Open My App imaage, drag and drop Applications alias there.

4. Drag and drop your *.app file to the image. 


5. Right click on the empty space in the image > Show View Options

    Select Background: Picture 

    Drag and drop *.png file from .background folder to the suggested window.

    Adjust Icons size, location, text size, etc.


6. Make the image read only 
    
    Open Disc Utility 
     
    Eject My App image 

    Go to Images > Convert > Select you *.dmg file 

    In the popup window change Image Format to: read-only, change name to app_name


You are ready !
