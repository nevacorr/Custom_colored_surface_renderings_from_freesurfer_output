1. Prior to running any scripts, change SUBJECTS_DIR to current directory using export SUBJECTS_DIR=$PWD

2. Open makeannotfilescript_xx_xxxx and modify regions if needed

3. Run makeannotfilescript_xx_xxxx scripts, use source instead of ssh

4. After running the makeannotfile scripts, open Freeview and load rh.pial and lh.pial. 

5. Choose "Annotation" menu and load newly created .annot file (eg rh.myparcmale.annot) for each surface

5. The colors are defined by the values in the xh_female_annot.ctab or xh_male_annot.ctab files. Make sure the same regions have the same colors in the male and female brain. Also make sure the .ctab files only have the regions that are to be colored and that they are numbered in sequence starting from 1.
