## instructions to obtain the general dataset

```sh
apt update && apt install unzip
mkdir -p data/archiv
wget -O data/archiv/LabPicsV1.zip https://zenodo.org/records/3697452/files/LabPicsV1.zip?download=1
unzip data/archiv/LabPicsV1.zip -d data/
```

## Download the medical and chemistry specific dataset from the project 
At this moment, not entirely sure what's the difference between the 2 with labpicsv1. But Chemistry specific dataset has categories that the labpicsv1 do not have. (Perhaps this source is continuously updated)
The official source is [here at Zenodo.org](https://zenodo.org/records/4736111)
```sh
wget -O data/archiv/LabPicsMedical.zip https://zenodo.org/records/4736111/files/LabPicsMedical.zip?download=1
wget -O data/archiv/LabPicsChemistry.zip https://zenodo.org/records/4736111/files/LabPicsChemistry.zip?download=1
unzip data/archiv/LabPicsChemistry.zip -d data/
unzip data/archiv/LabPicsMedical.zip -d data/
```