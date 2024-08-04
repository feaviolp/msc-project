# Addressing machine learning bias in criminal Justice using ontology: A study of recidivism in England and Wales
This is the repository of files to support the final project by Leigh Feaviour, studing MSc in Artificial Intelligence at the University of Essex.

The respository contains three folders:
## NIJ Analysis
This folder contains two Jupyter notebooks analysing the NIJ dataset which is in the NIJ Ontology folder:
- **NIJ EDA.ipynb** - A high level EDA in Python.
- **NIJ statistics.ipynb** - A detailed statistical analysis in R.
## NIJ Ontology
This folder contains:
- **NIJ_s_Recidivism_Challenge_Full_Dataset_20240222.xlsx** - The NIJ dataset, used in both the statistical analysis and the build of the NIJ ontology.
- **NIJ import rules.json** - The JSON rules to import the data.
- **NIJ_small.rdf** - A cut down version of the final ontology RDF file, to be opened in Protege (cut-down to save space). If the complete ontology is required then the RDF file should be downloaded and then the complete data imported using the JSON rules.
## MoJ Ontology
This folder contains:
- Three Excel data files:
  - **MoJ object instances.xlsx** - The object instances to build the data properties in ontology.
  - **MoJ correlation values.xlsx** - The correlation values of each feature to race and recidivism.
  - **MoJ offenders and cases.xlsx** - Dummy data of offenders and cases to test the ontology.
- **MoJ /various/.json** - Nineteen JSON files to import the data properties.
- **MOJ Correlation values.json** - The JSON file to import the correlation values.
- **MOJ Offenders.json** - The JSON file to import the dummy offenders.
- **MOJ Cases.json** - The JSON file to import the dummy cases.
- **MOJ.rdf** - The final MoJ ontology RDF file, to be opened in Protege.
The final ontology only has the first 100 out of 35,672 LSAO Residence codes and names imported to save space, because importing them all added nothing to the validation but increased the file size to over the 100MB limit for GitHub. The full data is in MoJ object instances.xlsx so if the complete ontology is required it can simply be downloaded and imported.
