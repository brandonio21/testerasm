Tester Homework 9
=================
######This is a small tweak to the original test script to work with homework 9.

Download script to your ieng6 account and create a directory called scripts
in your home directory.

1. Add exacutable permission to the script.
  ````bash
  chmod +x tester
  ````

2. Add and path to this script to your profile.
  ````bash
  'export PATH=$PATH:/home/linux/ieng6/cs12x/cs12xxx/scripts' >> ~/.bashrc
  ````
  *"cs12xxx" will need to be changed to your profile id.*

3. Then go into your homwework 9 folder and run the following command.
  ````bash
  tester Driver myTestfile -x
  ````
  The debug parameter is optional.
  
  *"myTestfile" is the name of the document that contains your test cases*
