
# CISC/CMPE 204 Modelling Project
We use a lottery game "Two color balls" as a model.
At first banker randomly choose：7 balls in total, 
choose 4 red balls from 33 different red balls (red ball 01, red ball 02, red ball 03, …., red ball 33), and
choose 3 blue balls from 16 different blue balls(blue ball 01, blue ball 02,.., blue ball 16).
Player w buy a random scratch card which have random 7 number.
The first four digits represent the numbers on red balls, the following three digits represent the number on blue ball.
And check if meet any prize winning condition, if player meet prize winning condition can get a big reward! See winning condition in our report!

## Structure
* `report` : Contains Summary, Constrainsts, Propositions, Model Exploration, First-Order Extension.
* `group_assignment_99.py` : check whether player meet any winning condition 
* `documents`: Contains folders for both of your draft and final submissions. README.md files are included in both.
* `run.py`: General wrapper script that you can choose to use or not. Only requirement is that you implement the one function inside of there for the auto-checks.
* `test.py`: Run this file to confirm that your submission has everything required. This essentially just means it will check for the right files and sufficient theory size.
