TODO for PowerShell OneNote enumerator  
Right now the thing is a function generator, and the function is barely useful.  but it meets checkpoint 1, which is that it spits out a hierarchical list of all pages in all of your OneNote notebooks.

TODO:
[ ] IMPLEMENT Register the function
  [ ] LEARN how to register the function so that it need not be re-loaded each session
    - Maybe a call to the script in .profile somewhere.
    - What about exec policy?
    - Maybe need to create a manual script to augment to augment .profile activities.
[ ] IMPLEMENT object creation
  - Right now it just OUTPUTS the data to the screen, so I don;t call this 'Get_OneNoteTOC yet, because it doesn;t really GET in a useful fashion.
  [ ] IMPLEMENT retrieving other fields, such as date last accessed, and critically, categories.
  
  
