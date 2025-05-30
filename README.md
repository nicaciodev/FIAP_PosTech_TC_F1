# FIAP / Pos-Tech / Tech Challenge / Fase 01
___
#### [RM363334]
#### Robson Nicácio R. dos Santos
___
#


## Objetivo
Tarefa de regressão: estimar valor do plano de saúde (custos hospitalares).

#

## Como Executar Online
#### Upload Manual pela Interface do Colab (google):

1. Acesse [colab.research.google.com](colab.research.google.com).
2. Clique em Arquivo > Fazer upload de notebook....
Navegue até o arquivo tech_challenge.ipynb e selecione-o.

#### Sincronização com Google Drive:

1. Faça upload do seu arquivo tech_challenge.ipynb para o seu Google Drive.
2. No Google Colab, clique em Arquivo > Abrir notebook.
Selecione a aba Google Drive e localize o tech_challenge.ipynb.

#### A partir do GitHub:

1. No Colab, [colab.research.google.com](colab.research.google.com), clique em Arquivo > Abrir notebook.
2. Selecione a aba GitHub, cole a URL do repositório ou do notebook específico, [aqui_o_link](https://github.com/nicaciodev/FIAP_PosTech_TC_F1/blob/main/tech_challenge.ipynb) e pressione Enter.


#
## Como Executar Localmente No Linux
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