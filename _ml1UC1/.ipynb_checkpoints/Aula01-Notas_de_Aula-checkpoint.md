PROMPT DE COMANDO

mkdir c:\_m1Uc1
cd _m1Uc1
mkdir c:\m1Env
cd m1Env

python -m venv ./
.\Scripts\activate.bat ou no Power Shell .\Scripts\Activate.ps1
python.exe -m pip install --upgrade pip
pip install pandas numpy
pip install matplotlib seaborn
pip install scikit-learn openpyxl
pip install xlsxwriter torch

cd ..
pip list
pip freeze > requirements.txt
pip install -r requirements.txt

pip install ipykernel
python -m ipykernel install --user --name=Machine_Learning --display-name "Python ML (venv)"
(salva do AppRoaming e não na pasta venv criada)

pip install jupyter lab
jupyter lab
http://localhost:8888/lab
http://127.0.0.1:8888/lab?token=4dc33d99e3ab12339e8467b7dde531f56e4212e79a4f78b6
Ctrl C 2 vezes encerra jupyter

python venv abre python colab
selecionar kernel python 3
ctrl Enter para rodar código