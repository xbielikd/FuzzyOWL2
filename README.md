# FuzzyOWL2
FuzzyOWL, Protége 4.3 and Gurobi installation 

Requirements: Java 8, Protége 4.3, FuzzyOWL2, Gurobi

Java 8:

Download from: https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html

Registration is needed.

After that, you can download Java SE Development Kit 8u181. What type depends on your OS.

Protége:

Download from: https://protege.stanford.edu/download/protege/4.3/

We need version 4.3 because we are sure that this version of Protége is compatible with FuzzyOWL2.

Download with Java VM.

FuzzyOWL2:

Download from https://www.umbertostraccia.it/cs/software/fuzzyDL/fuzzyDL.html

Contains fuzzyDL reasoner, Fuzzy OWL2 parser and Protége 4.3 plug-in.

Download and unzip to the new directory. The "FuzzyDL" is the main folder.

Gurobi:

Firstly we need to register on: https://www.gurobi.com 

Gurobi licence should be free for academic reasons, try to register with academic email.

If there is not version 8.1.1 available on the website, try this link https://packages.gurobi.com/8.1/Gurobi-8.1.1-win64.msi

After downloading and instalation we need to activate our license.

MY ACCOUNT > Licenses > Review your current licenses > your license > install > grbtkey

After opening Gurobi solver app on your PC, you wil be asked to type your license key. (If you use academic license, you will probably need to be connected on academic network.)

In order to allow executable files to be found when needed, you have to modify a few environment variables:

    • GUROBI_HOME should point to the <installdir>.
    
    • PATH should be extended to include <installdir>/bin.
    
    • LD_LIBRARY_PATH should be extended to include <installdir>/lib.


