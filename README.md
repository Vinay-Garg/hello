# hello

# This program can be used to create large text files of any size(in GB).

By default, it will create 6 files of namely: 1GB, 2GB, 3GB, 4GB, 5GB, 6GB.
it can take time depending on the system you are using.

you can modify according to your requirement by:
  open "make_.py"
  go to line 7
   change -> range(1,x)   (x = size in GB)
   
WARNING:
By default this program will generate continous file that is in sequence like 1GB, 2GB and so on.
If you want to get file of particular size
You can:
  open "make_.py"
  remove line 7 (first for loop)
  (take care of next indentation)
  change -> range(1,12*x+2)   (x = size in GB)
  
This way you will get only 1 file of required size.
