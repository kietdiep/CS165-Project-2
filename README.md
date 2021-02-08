# CS165-Project-2

## Part 1 : Authenticate_yourself.exe
The flag for our project is: 34gdfh340234

The way that we solved this portion of the lab was to search for the the phrase "incorrect password". After doing a text search to find the specific subroutine for the incorrect user/pass jump, we changed it to jump directly to the flag subroutine instead.

## Part 2 : WinEdt.exe
For the pop-up portion of this lab, we tried to find where the program began and doing a search for the label "start" got us to where we needed to look. From there at the bottom of the code we found two jumps, one to continue to the main program and one to jump to the popup. By changing the jbe code to a jmp, it completely skips the jmp to a popup and continues to executes the program code. 

In terms of how to get passed the banner. We searched for any terms related to "expired", "trial" , and "period". From there we switched over to graph view to find all jumps to the code blocks that had a trial period text inside. Once we found the jumps, we changed their jump location to skip past the trial location banner and go to the location following it. 
