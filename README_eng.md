ICONS
======

This repository contains icons for ```Nanit Discovery```.
To apply these icons, you need to use an ```SD``` or ```microSD``` memory card through a suitable adapter to the memory card slot used by ```Nanit```.

Preparation of the memory card
------------------------------

The memory card must support the `FAT16` or `FAT32` (`dosFAT`) file system. Attention: ```Nanit``` card reader currently does not support other file systems - including ```exFAT```!

If the memory card is formated for a different file system, it should be formatted to the recommended file system.

We copy, clone, or unpack the archive containing the icons into the root of the file system.

        \                   \           
        |                   |           
        +-\i18n             | New                  
        |    |              | directory          
        |    +-\ukr         | structure                   
        |    |   |          |                    
        |    |   +-1.bmp    |                          
        |    |   +-3.bmp    |                          
        |    |   +-4.bmp    |                          
        |    |   +-5.bmp    |                          
        |    |   +-6.bmp    |                          
        |    |   +-7.bmp    |                          
        |    |   +-8.bmp    |                          
        |    |   +-9.bmp    |                          
        |    |   .......    |                          
        |    |   +-XXX.bmp  |                            
        |    |              |                
        |    +-\eng         |                     
        |    |   |          |                    
        |    |   +-1.bmp    |                          
        |    |   +-2.bmp    |                          
        |    |   .......    |                          
        |    |   +-XXX.bmp  |                            
        |    |              |                
        |    +-\len         |                     
        |    ......         |                     
        |    +-\YYY         /                     
        |                              
        +-D1.bmp            \                  
        +-D2.bmp            | Saved                  
        +-D3.bmp            | for
        .........           | compatibility                
        +-FF.bmp            /    

In the root of the file system there should be a directory `i18n` (Generally accepted number name "internationalization" in lower case). The directory should contain subdirectories named according to language codes that comply with the __ISO 639-2__ standard. Directory names must be written in lower case.

Abbreviated table of codes
--------------------------
|CODE| LANGUGE |
|:-:|:--------:|
|ukr| Ukranian |
|eng| English  |
|...|..........|
|xxx|__________|



                                  
Name table of the old file structure
--------------------------------------

To maintain compatibility with common sets, there are icon files in the root directory of the memory card.

File names are formed according to the following scheme
```hex([Mode number]+0xD0).bmp```

|Mode number | Old name | New name|
|:----------:|:--------:|:-------:|
|      1     |  D1.bmp  |  1.bmp  |
|      2     |  D2.bmp  |  2.bmp  |
|      3     |  D3.bmp  |  3.bmp  |
|      4     |  D4.bmp  |  4.bmp  |
|      5     |  D5.bmp  |  5.bmp  |
|      6     |  D6.bmp  |  6.bmp  |
|      7     |  D7.bmp  |  7.bmp  |
|      8     |  D8.bmp  |  8.bmp  |
|      9     |  D9.bmp  |  9.bmp  |
|     ...    |   ...    |   ...   |
|     NUM    |   HEX    |   NUM   |









