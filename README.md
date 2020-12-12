Parallel-DBSCAN-based-on-Spark
===========================
Implementation of the parallel DBSCAN based on Spark -- MSBD5003 Group Project.

### File Structure
```
DBSCAN-based-on-Spark
├── 1.reading materials
│   └── introduction.txt
├── 2.dataset
│   ├── D31.txt
│   ├── R15.txt
│   ├── aggregation.txt
│   ├── dim032.txt
│   ├── pathbased.txt
│   ├── spiral.txt
│   └── yeast.txt
├── 3.code
│   ├── Parallel_BOUNDARY_BASED_SPLIT_DBSCAN.ipynb
│   ├── Parallel_COST_BASED_SPLIT_DBSCAN.ipynb
│   ├── Parallel_Matrix_DBSCAN.ipynb
│   └── algorithm.txt
├── 4.report
│   ├── 5003_Group12_Final_PPT.pdf
│   ├── 5003_Group12_Final_PPT.pptx
│   ├── 5003_Group12_Final_Report.pdf
│   ├── proposal.pdf
│   └── report.txt
├── 5.image
│   ├── 1607700922502.jpg
│   ├── 1607700951759.jpg
│   └── image.png
└── README.md
```
### Task Description:
This project is about how to implement some parallel DBSCAN algorithms on Spark. Firstly, by looking through the materials provided in reading materials, we could get some basic ideas about how to implement the DBSCAN in a parallel way. Secondly, there are some datasets providing for testing the corresponding algorithm codes. Thirdly, parallel DBSCAN algorithms are implemented by using jupyter-notebooks in the code folder. Fourthly, the proposal and final report are used to introduce the details about our project and parallel DBSCAN algorithms.  


## Dues:

- **2020/10/18** **Proposal Submission**
- **2020/11/24** **Presentation**
- **2020/12/20** **Final Report and PPT**


## Environment Information:

|environment|version|
|----|-----|
|`spark`|spark-3.0.0-bin-hadoop2.7.tgz|
|`JDK`| jdk-8u261-windows-x64.exe|
|`hadoop`|hadoop-2.7.7.tar.gz|
|`packages`|...|


## Results Display:
Here we show one data-set of four we used - Aggregation:
![image](https://github.com/DataconTom/DBSCAN-based-on-Spark/blob/main/5.image/1607700922502.jpg)
![image](https://github.com/DataconTom/DBSCAN-based-on-Spark/blob/main/5.image/1607700951759.jpg)
