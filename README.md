CSE 30 tester
=================
######Version **.01** of pa tester for CSE 30.

Create a directory in your home directory called 'scripts' and put the `tester` script in it.

1. Add exacutable permission to the script.
  ````bash
  chmod +x tester
  ````

2. (optional) Add a path to this script to your profile.
  ````bash
  'export PATH=$PATH:/home/solaris/ieng9/cs30x/cs30xxx/scripts' >> ~/.bash_profile
  ````
  If for some reason this gives you an error just open ~/.bash_profile in vim and paste the export command somewhere in the middle.

  *"cs12xxx" will need to be changed to your own profile id.*

3. Then go into your pa# directory folder and run the following command.
  ````bash
  tester pa# pa#test filename
  ````
  *filename* is the file with your test cases. I have included a *very* small
  test case called `testa` which can get you started.

  You will be asked if you would like to append to an existing test file or
  overwrite the old one. The test file and your will both be run the both
  will be opened in vimdiff for comparison.

  *"mine" is the name of the document that contains your test cases*
  *"sol" is the name of the document that contains the solutions test cases*

