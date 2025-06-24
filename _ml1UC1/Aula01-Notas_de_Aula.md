PROMPT DE COMANDO

mkdir c:_m1Uc1 
cd _m1Uc1 mkdir 
c:\m1Env 
cd m1Env

python -m venv ./ 
.\Scripts\activate.bat ou no Power Shell .\Scripts\Activate.ps1 

python.exe -m pip install --upgrade pip 
pip install pandas numpy 
pip install matplotlib seaborn 
pip install scikit-learn openpyxl 
pip install xlsxwriter torch

pip install pandas numpy matplotlib seaborn scikit-learn openpyxl xlsxwriter torch

cd .. 
pip list pip freeze > requirements.txt 
pip install -r requirements.txt

pip install ipykernel python -m ipykernel install --user --name=Machine_Learning --display-name "Python ML (venv)" (salva do AppRoaming e não na pasta venv criada)

pip install jupyter lab 
jupyter lab 
http://localhost:8888/lab?token=4dc33d99e3ab12339e8467b7dde531f56e4212e79a4f78b6 
http://127.0.0.1:8888/lab?token=4dc33d99e3ab12339e8467b7dde531f56e4212e79a4f78b6
http://localhost:8888/lab?token=909028c9b9588c3baa91ad83f5b2f88d9ee01ca7e44e5986
http://127.0.0.1:8888/lab?token=909028c9b9588c3baa91ad83f5b2f88d9ee01ca7e44e5986

//CASA 
http://127.0.0.1:8888/lab?token=a95766afec8d4ab6a77e73fb12f814d89e9eebd893881aab 
http://localhost:8888/lab?token=a95766afec8d4ab6a77e73fb12f814d89e9eebd893881aab

Ctrl C 2 vezes encerra jupyter

python venv abre python colab selecionar kernel Python ML (venv) 3 ctrl Enter para rodar código

Abrir jupiter:
- C:\Analise_Dados_Python\_m1Uc1\m1Env\Scripts\activate.bat
- cd C:\Analise_Dados_Python\_m1Uc1
- jupyter lab
Abrir Jupyter em casa:
-cd E:\CienciaDadosPython\CienciaDados2\_m1Uc1\m1Env\Scripts
-.\Activate.ps1 
-cd E:\CienciaDadosPython\CienciaDados2\_m1Uc1 ou cd .. 2 vezes
-jupyter lab

Rodar arquivos python .py para gerar planilha csv:
-Passos acima
-cd C:\Analise_Dados_Python\_m1Uc1\Machine-Learning-UC1-Alunos\Aula01
(quantidade e id_inicial após o nome do arquivo)
-python ./gerador_dataset-010-relacaionados.py 100 1
-python ./gerador_dataset-020-realista.py 100 101
-python ./gerador_dataset-030-nao_direto.py 100 201
-python ./gerador_dataset-040-simples.py 100 301
-python ./gerador_dataset-020-realista.py 5000 1

Fazer a unidade1 utilizando dataset realista explicando os códigos com 5000

Perguntar para IA sobre as linhas de gerador de dataset os 4

Permitir execução de Scripts no powerShell:
-Set-ExecutionPolicy Unrestricted
-Digite S