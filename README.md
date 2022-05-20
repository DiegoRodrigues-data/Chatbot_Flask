
# Obsrvações

o ambiente de instalação utilizado foi o anaconda https://www.anaconda.com/ utilizando -- Python 3.7.13 chat configurado para português

# 1 - 
conda install tensorflow==2.4.1
# 2 - 
conda install nltk==3.7
# 3 - 
pip install -U Flask to install Flask==2.1.2
# 4 - 
conda install Keras==2.3.1

# Servidor WEB

Já está incluso nessa implementação um servidor web em Flask que se conecta ao modelo treinado via Aprendizagem de Máquina. após a instalação do ambiente a execução correta é no endereço local http://127.0.0.1:5000/

# Treinamento do Modelo

Para treinar execute o comando [Python train.py]  o arquivo com os dados para treino é [intents.json] o resultado será po modelo treinado [chatbot_model.h5]

# Projeto Original
Fork do repo:
https://github.com/mainadennis/An-AI-Chatbot-in-Python-and-Flask

