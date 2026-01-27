# Graph examples in PySpark with Jupyter Notebook

Tested to run on Spark 4.1.1 with GraphFrames 0.10.0

## Installation:
1. Create Python virtual environment and activate
2. Install dependencies (```pip install -r requirements.txt```)
3. Run Jupyter Notebook (```jupyter-notebook```)

If you'd like to use PySpark without jupyter use the follwing command:

```pyspark --packages io.graphframes:graphframes-spark4_2.13:0.10.0```


### Installation on Windows ###
Tested using Windows 11 with Java JDK 17, pyspark 4.1.1 and Python 3.13
1. Install Java JDK 17, for example the Temurin distribution (https://adoptium.net/) using chocolatey (```choco install temurin17```)
2. Spark on Windows needs a tool called "winutils.exe" which use to be distributed with Hadoop but isn't part of it anymore.  You can find it here: https://github.com/cdarlint/winutils
3. Clone the repo ```git clone https://github.com/cdarlint/winutils.git```
4. Set the HADOOP_HOME environment variable pointing to the winutils folder for a given Hadoop version, for example the latest: ``set HADOOP_HOME=c:\dev\winutils\hadoop-3.3.6``
5. The rest is the same as on Linux/Mac OS - clone this repo, create a standard Python virtual environment (``python -m venv .venv``) activate it (``.venv\Scripts\activate``) and install the dependencies (```pip install -r requirements.txt```).
6. Run Jupyter Notebook (```jupyter-notebook```)

 
