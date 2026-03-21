https://github.com/m22aie221/CSL7100-Assignment3/tree/main

cd /home/rajesh/CSL7100

cd /home/rajesh/CSL7100/Assignment3


git init
git status
git add Question1 Question4 Question5_6 Question10 Question11 Question12 Question7 song.txt 
git status
git commit -m "Assignment 3"
git log
git remote add origin git@github.com:m22aie221/CSL7100-Assignment3.git
git remote -v
gitt branch -M main
git push -u origin main


#starting hdfs

stop-all.sh


start-all.sh
cd /home/rajesh/CSL7100/PySpark/pyspark-tutorial
python -m venv .pyspark-env
source .pyspark-env/bin/activate
cd /home/rajesh/CSL7100
jupyter-lab


#Task_6
cd /home/rajesh/CSL7100/Assignment3/Part3_MatrixFactorization
python -m venv .svd_surprise_env
source .svd_surprise_env/bin/activate