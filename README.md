# MBIO-4783_F2023-Project-Group-13
Project files for Group 13 in Dr. Pan's MBIO 4783/5783 class at OU in the Fall 2023 semester.

In order to run this file, you must have a .csv file with the appropriate formatting (see data in repository for examples). The data included has been base called and sorted by number of reads and probability of modifications (>=20 reads and >=90% probability), however the program works with data outside of this range.

Before running the program, please pull all files and ensure your path to your data is accurate. The path should include the file itself.

When the program starts, a GUI will open. If you do not immediately see a GUI, check your open applications before restrating the program; usually the GUI is hidden behind one of these. From within the GUI, you are able to type in genes of interest one-by-one into a window that opens after clicking the "Add Gene" button. When entering a gene, make sure to not include any special characters like hypehns or periods. Furthermore, if your gene of interest includes a Greek letter, insert the corresponding English letter instead (i.e. instead of "alpha", enter "a"). This input is NOT case sensitive.

The current dictionary is limited due to the scope of the inital project, but genes can be easily added to it if needed. To do this, edit the program in a Python editor (such as Jupyter Notebook), adding in any desired genes. The program converts gene names to their respective Ensembl ID, as that is the output from our data we chose to focus on due to its ease of use and high unlikelihood to cause incorrect hits off of a particular read.
