# FIAP / Pos-Tech / Tech Challenge / Fase 01
___
#### [RM363334]
#### Robson Nicácio R. dos Santos
___
#


## Objetivo
Tarefa de regressão: estimar valor do plano de saúde (custos hospitalares).

#
## Como Executar No Linux
1. Caso necessário, instale o [git] para começar.

No Debian:
```
apt-get install git ;\
apt install python3.11-venv
```

#
2. Baixe o projeto:
```
git clone "https://github.com/nicaciodev/FIAP_PosTech_TC_F1.git" ;\
cd FIAP_PosTech_TC_F1
```
##
3. Crie o ambiente virtual e o ative:
```
python3 -m venv env ;\
source env/bin/activate
```
##
4. Atualize o pip:
```
pip3 install --upgrade pip
```
#
5. Instale as bibliotecas necessária no ambiente virtual:
```
pip3 install -r requiriments.txt
```
##
6. Abra o JupyterLab com o Tech-Challenge:
```
jupyter lab tech_challenge.ipynb
```
##
#### Obs: Para encerrar, basta fechar o terminal ou 2x [CTRL+c] .
#### Obs2: Também disponível em PDF, arquivo [Tech-Challenge.pdf].