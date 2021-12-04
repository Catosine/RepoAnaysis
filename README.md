# Repo Analysis
This repo is used for analysing file activity in [openstack/neutron](https://github.com/openstack/neutron) by [Pengnan](pengnan.fan@mail.mcgill.ca). 

## Run Script
Just open the [Jupytor Notebook](./RepoAnalysis.ipynb) and run all.

## Facts
### Which parts of the repository is investigated?
Anything under `/neutron` of [openstack/neutron](https://github.com/openstack/neutron).

### How long is the time period investigated?
The time period investigated is arount **6 months** (Anything after 2021/06/01 till present).

### How many commits occurred during the studied period?
According to the script, there are **472** commits that fulfill the requirements (which means each of them are created within the timeslot and editions happend under `/neutron`).

### How much edition occurred during the studied period?
According to the script, the top-12 most frequent edited modules are:
| module | add | delete | total |
|--------|-----|--------|-------|
| tests  |18394|7000|25394|
|plugins| 4265 | 2274 | 6539|
|db| 4050 |1629| 5679|
|agent| 2886 | 877 |3763|
|services| 1748 | 972 | 2720|
|extensions| 897 | 52 | 949|
|objects| 722 | 213 | 935|
|cmd| 929 | 4 |933|
|quota| 178 | 382 |560|
|common| 338 | 148 | 486|
|conf| 390 | 79 | 469|
|api| 234 | 151 | 385|  
In short, there are **48812** modifications where **35031** of them are additions and **13781** are deletions.