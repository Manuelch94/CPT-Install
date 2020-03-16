# CPT-Install
A guide to install Climate Prediction Tool in Ubuntu

Software download and instructions can be found at: https://doi.org/10.7916/d8-86dy-wq10

**But**, there`s no consistency whit in these instructions and software version offered above. So, I manage to create these new installation commands according the software version 16.4.1.

Once downloaded inside your preferred folder open a new terminal and type:

To extract contents:
```bash
tar -xvzf CPT.16.4.1.tar.gz
``` 

Then get inside the folder:
```bash
cd CPT/16.4.1/ 
```

And compile, _this may take a while_:
```bash
make -f Makefile
```









