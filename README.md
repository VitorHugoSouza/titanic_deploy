# titanic_deploy
Deploy de um modelo de ML para predição do dataset do TITANIC


Este é um projeto simples para elaborar como implantar um modelo de aprendizado de máquina usando a API Flask

**Pré-requisitos** 

Você deve ter Scikit Learn, Pandas (para o modelo Machine Leraning) e Flask (para API) instalados.

**Estrutura do Projeto**


Este projeto tem quatro partes principais:

finalized_model.py - contém o código para nosso modelo de aprendizado de máquina.

app.py - Contém APIs Flask  com de chamadas de GUI ou API, calcula o valor com base em nosso modelo e o retorna.

modelo - esta pasta contém o modelo HTML (index.html) para permitir que o usuário insira os dados

estatico - esta pasta contém a pasta css com o arquivo style.css, que tem o estilo necessário para o arquivo index.html.

**Executando o projeto**

Certifique-se de estar no diretório inicial do projeto. Crie o modelo de aprendizado de máquina executando o notebook abaixo:

 Titanic.ipynb (notebook)

Isso criaria uma versão serializada de nosso modelo

Execute app.py usando o comando abaixo para iniciar a API Flask

```python app.py```


Por padrão, o flask será executado na porta 5000.

Navegue até o URL http://127.0.0.1:5000/ (ou) http://localhost:5000
Você deve conseguir visualizar a página inicial.


