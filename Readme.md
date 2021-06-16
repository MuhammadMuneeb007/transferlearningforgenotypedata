### This step was performed on linux machine.
### Download the software HAPGEN2
https://mathgen.stats.ox.ac.uk/genetics_software/hapgen/hapgen2.html#Download_and_Compilation

1. Extract the downloaded file and rename it to hapgen.
There will be hapgen2 file and lisence file.

2. Download the example file
https://mathgen.stats.ox.ac.uk/genetics_software/hapgen/download/example/hapgen2.example.tgz
Extract the files and rename the folder to "example".
Move this example folder to hapgen folder.

3. Open "hapgen" folder in terminal and run the follow command to make sure everything is working fine.

./hapgen2 -m ./example/ex.map -l ./example/ex.leg -h ./example/ex.haps -o ./example/ex.out -dl 1085679 1 1.5 2.25 2190692 0 2 4 -n 100 100 -t ./example/ex.tags

If Output is this 
"HAPGEN took 0 seconds to complete. Have a nice day!"
it means everything working fine.



