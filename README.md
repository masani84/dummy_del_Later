write all steps here
................
create folder at local
copy path
open cmd promt
cd path
code .


conda create -p venv python=3.8
conda activate venv 
or
conda activate C:\SIVA\INEURON\VC_Env_Dummy\venv
crate .gitignore (add venv inside .gitignore)
create README.md
craete requirements.txt
	numpy
	python
	Flask
create setup.py (add code to setup.py file)
python setup.py install

add components
__init__.py
data_ingestion.py
data_tarnsformation.py
model_trainner.py

add pipeline
__init__.py
pred_pipeline.py
train_pipeline.py

exception.py
logger.py
util.py
........................