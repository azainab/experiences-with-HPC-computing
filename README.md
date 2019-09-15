# experiences-with-HPC-computing

cd $SCRATCH

cd python_project

activate virtual_env

source venv/bin/activate

module load python/3.6.5-generic

python Spark\ load\ forecasting\ spaindataset.py

pip install pandas

pip install pyspark
 
python xx.py


## pip version issues (latest version of pip)
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python get-pip.py --user
