# UltimateElectionSimulator
by EuroNutella

This is a tool that should help you generate random percentages for as many parties as you want.

After inputting the number of parties, and naming them, you will be given a choice between 4 modes to generate your percentages.

random percentages (r like random) will generate random integers that sum up to 100 and randomly assign them to each party. Turnout is a random number between the minimum and maximum turnout you set up. You may add a mode with electoral thresholds that tells you if a party passed or not.

adjusted percentages (a like adjusted) will ask you to input some integers that indicate what percentages does each party already have (or whichever percentage you want it to have) and will generate random percentages that can be at most x points less or x points more than the current one, where x is the range you provided it. Percentages will sum to 100. This is useful if you want parties that don't deviate too much from a certain value or from previous elections. Turnout is a random number between the minimum and maximum turnout you set up. You may add a mode with electoral thresholds that tells you if a party passed or not.

population votes (random turnout) (v like votes) will ask you to input an integer representing your population. The program will then generate random numbers up to that integer, then divide them by the max population to get the percentages (rounded to 2 decimals). All the votes will sum to the max population. Turnout is a random number between the minimum and maximum turnout you set up.

population votes (true turnout) (t like turnout) works similiarly to pop votes (random turnout) but instead of all the generated votes summing up to the max population there could be people that didn't vote. Turnout is the total votes divided by the max population, then multiplied by 100 and rounded to 2 decimals.

Approval influenced (i like influenced) works a lot like adjusted percentages mode but it takes into account the approval rating (rounded to an integer you'd like). Essentially approval rating is used as the chance for the governing parties to increase their popularity, this means a high approval rating will mean a higher chance the governing parties will have a bigger percentage, while on the contrary a low approval rating will mean they have a higher chance of losing percentage points.

############
REQUIREMENTS
############

Windows 10 or newer
NOTE: I only tested it on windows 10and cannot guarantee it works on newer versions.
Side-note for LINUX: You can still use this program on Linux by running "python3 UltimateElSim.py" from the console after navigating to the folder you saved it in. 

############
INSTALLATION
############

It should be very simple:

1) Download all the files
2) Put them in your preferred folder
3) navigate to the /dist folder and right click the .exe file
4) Hover over "Send to" and then click "Send to desktop (Create shortcut)" (This will create a desktop shortcut you can use and move to easily access the program)
