```
____ ___  _  _    ____ _    ____ ____ ___ ____ ____ _  _ _ ____ ____ 
|__| |__] |_/  __ |___ |    |___ |     |  |__/ |  | |\ | | |    [__  
|  | |__] | \_    |___ |___ |___ |___  |  |  \ |__| | \| | |___ ___] 
                                                                      
```
                                                                         
                                                                         
# Abrakabuki electronics

This repo contains all necessary files to design and produce PCBs for the Abrakabuki product range.

## File format and folder structure

Documentation files should be in PDF. Board image files can be in PNG or PDF.

PCB Design file are in EAGLE Standard edition (7.4) file format.

These are general rules to help maintain a consistent folder structure:

* All libraries are placed inside the shared libraries repository. It can be found
  on [Github](https://github.com/exmchina-dev/eagle-resources)  

* One board for each project folder.  

* Mutiples revisions can be placed inside a subfolder. i.e. ECS-Board/Rev A1  

* BOMs, partlists, spreadsheet should placed inside a BOMs/ folder.  

* Documentations files are in eagle-resources/doc or in doc/ inside a project folder.