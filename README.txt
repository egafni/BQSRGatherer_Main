Compiling
========
make sure .jar paths are correct

    javac -classpath ".:Queue-2.4-9-g532efad/Queue.jar:GenomeAnalysisTK-2.4-9-g532efad/GenomeAnalysisTK.java" BQSRGathererMain.java


Running
=======

java -cp /home/esg21/WGA/tools/Queue-2.4-9-g532efad/Queue.jar:. BQSRGathererMain test chr20.recal chr21.recal ...
