To work with exactly same dataset, start from executing:

run
train_test_set_creator.ipynb
	*input:
		*non_arguments_random_raw.csv
		*non_arguments_questions_raw.csv
		*domain_1_arguments_raw.csv
		*domain_2_arguments_raw.csv
	*output:
		*domain_1_set_clean.csv
		*domain_2_set_clean.csv


-------------------------

### Execute a jupyter notebook in a virtual env
https://stackoverflow.com/questions/33496350/execute-python-script-within-jupyter-notebook-using-a-specific-virtualenv

1. pip install virtualenvwrapper
2. virtualenv venv
3. .\venv\Scripts\activate
4. (venv) pip install jupyter
5. (venv) pip install ipykernel

Next, set up the kernel

6. (venv) python -m ipykernel install --name venv --display-name "Python3.10.2 (venv)"

Run jupyter notebook

7. (venv) jupyter notebook
8. in jupyter notebook select Krnel "Python3.10.2 (venv)"

9. install requirements.txt

