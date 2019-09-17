# experiences-with-HPC-computing

cd $SCRATCH

cd python_project

activate virtual_env

source venv/bin/activate

module load python/3.6.5-generic

pip install pandas

pip install pyspark
 
python Spark\ load\ forecasting\ xxx.py


## pip version issues (latest version of pip)
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python get-pip.py --user

![Screenshot](screenshot.png)
