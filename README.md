# DAP_PROJECT
# Analysis of COVID-19 Epidemic on Healthcare Industry and Ensued Effect on Mental Health
*************************************************************************************************************************************
# Index
1. [About system](#section1)<br>
2. [How To Run The Project on local machine](#section2)<br>
3. [Steps to follow](#section3)<br>
  - 3.1 [STEP I: MongoDB Run](#section301)<br>
  - 3.2 [STEP II: PostgreSQL Run](#section302)<br>
  - 3.3 [STEP III: Checkout in Git Branches](#section303)<br>
  - 3.4 [STEP IV: Run Common Data File and Visualization from Main Branch](#section304)<br>
  - 3.5 [STEP V: Check Data Stored or not](#section305)<br>
  - 3.6 [STEP VI: Check individual code](#section306)<br>
 4. [Thank You](#section4)<br>

*************************************************************************************************************************************

## 1. About system <a id=section1></a>
*************************************************************************************************************************************
<b>This application built in Python libraries, MongoDB, PostgreSQL, Matplotlib, and Plotly</b>

*************************************************************************************************************************************


## 2. How To Run The Project on local machine <a id=section2></a>

<b>Pre-requisites :</b><br>
       1. Clone the repository from URL"". <br>
       2. Install Anaconda and Python software’s on your machine. <br>
       3. Install MongoDB and PostgreSQL databases on your machine.

*************************************************************************************************************************************
## 3. Steps to follow <a id=section3></a>
### 3.1 STEP I: MongoDB Run	<a id=section301></a>
<b> To run this project, you must have to run mongo dB server and your client should open (Robo 3T or Mongo Compass) on your PC. </b>
1. To run mongo server, go to your mongo dB bin path <br>
<b>C:\Program Files\MongoDB\Server\4.4\bin</b> and run <b>mongod</b> command.

![mongod](https://user-images.githubusercontent.com/78203366/115843709-06c97080-a417-11eb-9141-6f38615b921b.PNG)



2. Make sure your client should be open and connected.


![connection](https://user-images.githubusercontent.com/78203366/115843470-c8cc4c80-a416-11eb-9b1b-7409f2e6448b.PNG)

*************************************************************************************************************************************



### 3.2 STEP II : PostgreSQL Run	<a id=section302></a>
<b>Start pgAdmin for PostgreSQL database. </b>

![pgAdmin](https://user-images.githubusercontent.com/78203366/115843927-442dfe00-a417-11eb-90a4-9c86c59e1f44.PNG)

*************************************************************************************************************************************


### 3.3 STEP III: Checkout in Git Branches	<a id=section303></a>
<b>To run individual Jupyter file need to checkout in branches to see the code</b>

1. In the clone directory there are 4 different branches.

![gitbranches](https://user-images.githubusercontent.com/78203366/115844269-95d68880-a417-11eb-883b-9f9fff7c2e7d.PNG)


2. Checkout in any branch as per your choice, for git checkout you can use **Git Commands** document for your reference. <br>
<b>git checkout <branch_name></b>

*************************************************************************************************************************************


### 3.4 STEP IV: Run Common Data File and Visualization from Main Branch<a id=section304></a>

<b>Open Anaconda Jupyter and go to the clone directory.  Open <b>Final_version.ipynb</b> file and run. </b>

1. In the branch there is a **Final_version.ipynb** file available open it in the jupyter notebook.
! ![final](https://user-images.githubusercontent.com/78203366/115844838-2a40eb00-a418-11eb-959a-80df12bfd266.PNG)

2. In the file there are some libraries required before running, <b>you need to uncomment and install those libraries first then comment once it is installed. </b>
![libraries](https://user-images.githubusercontent.com/78203366/115844725-08dfff00-a418-11eb-84f3-7dc6f24cf18f.PNG)

3. Finally run the code start to end.

*************************************************************************************************************************************

### 3.5 STEP V: Check Data Stored or not <a id=section305></a>

<b>Check database (Robo 3T collection, PostgreSQL) created, and data inserted successfully and visualization. </b> <br>

*************************************************************************************************************************************


### 3.6 STEP VI: Check individual code <a id=section306></a>
<b>To check individual data visualization you should have to checkout into **specific branch. **</b> and run .ipynb file <br>
* Use command **git checkout <branch_name>**
*************************************************************************************************************************************
# Thank You! <a id=section4></a>
*************************************************************************************************************************************


