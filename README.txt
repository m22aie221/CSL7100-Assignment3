https://github.com/m22aie221/CSL7100-Assignment3/tree/main

cd /home/rajesh/CSL7100

cd /home/rajesh/CSL7100/Assignment3


git init
git status
git add Question1 Question4 Question5_6 Question10 Question11 Question12 Question7 song.txt 
git status
git commit -m "Assignment 2"
git log
git remote add origin git@github.com:m22aie221/CSL7100-Assignment2.git
git remote -v
gitt branch -M main
git push -u origin main


#starting hdfs

start-all.sh
stop-all.sh


cd /home/rajesh/CSL7100/PySpark/pyspark-tutorial
python -m venv .pyspark-env
source .pyspark-env/bin/activate
cd /home/rajesh/CSL7100/Assignment2