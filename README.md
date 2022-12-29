## Prepare work env

### How to install bigdatasetup (spark, hadoop, jdk)
https://www.youtube.com/watch?v=LrpxfCxmMeo

jdk 11.0.14 (https://www.oracle.com/java/technologies/javase/jdk11-archive-downloads.html)

spark 3.2.3 (https://www.apache.org/dyn/closer.lua/spark/spark-3.2.3/spark-3.2.3-bin-hadoop2.7.tgz)

hadoop 2.7.1 - winutils.exe (https://github.com/steveloughran/winutils/tree/master/hadoop-2.7.1/bin)

### PySpark tutorial
https://www.youtube.com/watch?v=_C8kWso4ne4&t=2268s

### Install requirements.txt
pip install -r requirements.txt

### Setup Env Variables (Windows)
* HADOOP_HOME = <C:\work_space\bigdataseetup\hadoop>
* JAVA_HOME = <C:\Program Files\Java\jdk-11.0.14>
* SPARK_HOME = <C:\work_space\bigdataseetup\spark>

#### Add to PATH env variable
* %JAVA_HOME%\bin
* %HADOOP_HOME%\bin
* %SPARK_HOME%\bin