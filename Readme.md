### This step was performed on a linux machine.
### Download the software HAPGEN2
https://mathgen.stats.ox.ac.uk/genetics_software/hapgen/hapgen2.html#Download_and_Compilation

### 1. Extract the downloaded file and rename it to hapgen.
There will be a hapgen2 file and a lisence file.

### 2. Download the example file
https://mathgen.stats.ox.ac.uk/genetics_software/hapgen/download/example/hapgen2.example.tgz
Extract the files and rename the folder to "example".
Move this example folder to the hapgen folder.

### 3. Open the "hapgen" folder in the terminal and run the following command to make sure everything is working fine.

./hapgen2 -m ./example/ex.map -l ./example/ex.leg -h ./example/ex.haps -o ./example/ex.out -dl 1085679 1 1.5 2.25 2190692 0 2 4 -n 100 100 -t ./example/ex.tags

If Output is this 
"HAPGEN took 0 seconds to complete. Have a nice day!"
it means everything is working fine.

### 4. Go to this link 
https://mathgen.stats.ox.ac.uk/impute/data_download_1000G_pilot_plus_hapmap3.html
and download the dataset for two populations "CEU" and "YRI." In our case, YRI is a large population, and CEU is a small population.


### 5. Extract the files rename them correspondingly.

### 6. We need three files for each population to generate data.
XXXX.hap
XXXX.leg
XXXX.map


### 7. We will generate data for the first chromosome only.

### 8. Let's simulate data for the CEU population. These steps are also the same for the YRI population expect the number of cases/controls to be generated. For CEU, it is 50 cases and 50 controls, and YRI is 1000 cases and 1000 controls.


### 9. Open 1000 genome pilot and hapmap3 file folder for CEU population.

Files are in this format.

MAP FILE

genetic_map_chr1_combined_b36.txt 
genetic_map means it is a map file.
chr1 means it is chromosome 1. 

Rename this file to CEU.map

HAP FILE
pilot1.jun2010.b36.CEU.chr1.official.haps

Rename the file to CEU.haps

LEG file
pilot1.jun2010.b36.CEU.chr1.official.legend

Rename the file to CEU.leg

COPY THESE 3 files to the "example" folder.


### 10. 
