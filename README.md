CSE 30 tester .01
=================
######Version .01 of hw tester for CSE 30.

Download script to your ieng9 account and create a directory called scripts
in your home directory.

1. Add exacutable permission to the script.
  ````bash
  chmod +x tester
  ````

2. Add a path to this script to your profile.
  ````bash
  'export PATH=$PATH:/home/solaris/ieng9/cs12x/cs12xxx/scripts' >> ~/.bash_profile
  ````
  If for some reason this gives you an error just open the file in vim and
  paste the export command somewhere in the middle.

  *"cs12xxx" will need to be changed to your profile id.*

3. Then go into your pa# directory folder and run the following command.
  ````bash
  tester pa# pa#test filename
  ````
  *filename* is the file with your test cases. I have included a *very* small
  test case called `tasta` which can get you started.

  You will be asked if you would like to append to an existing test file or
  overwrite the old one. The test file and your will both be run the both
  will be opened in vimdiff for comparison.

  *"mine" is the name of the document that contains your test cases*
  *"sol" is the name of the document that contains the solutions test cases*

