# iCanHazShortcut
Simple shortcut manager for OS X 10.8 or higher.  
![screenshot](https://eri.deseven.info/scr/MidfacialParliamentaryPeriphrasis.png)  

## binaries
Latest binary release can be downloaded [here](https://deseven.info/sys/ichs.zip).  

## compiling from source
iCHS created in [PB](http://purebasic.com) and depends on [pb-osx-globalhotkeys](https://github.com/deseven/pb-osx-globalhotkeys).  
1. Obtain the latest LTS version of pbcompiler, install it to ```/Applications```.  
2. Install xcode command line tools by running ```xcode-select --install```.  
3. Clone iCHS repo.  
4. Clone ```pb-osx-globalhotkeys``` module to neighboring directory.  
5. Run the included ```build/build.sh``` script to build the app. If you want codesigning then provide your developer ID as a first argument.  