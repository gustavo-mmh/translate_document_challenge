# Translate Document Challenge

Este repositório contém um projeto que implementa a tradução de páginas da web. O projeto é escrito em Python e inclui os arquivos principais `main.py`, `requirements.txt` e `setup.py`.

## Funcionalidades

- **Tradução de Páginas da Web:** Implementa a tradução de páginas da web utilizando uma biblioteca Python. 
- **Configuração Simples:** Fácil de configurar e usar com instruções claras. 
- **Extensível:** Pode ser adaptado para incluir mais funcionalidades conforme necessário.

## Stack Tecnológica 

- **Linguagem:** 
Python 
- **Bibliotecas:** As bibliotecas específicas utilizadas para a tradução estão listadas no arquivo `requirements.txt`.

## Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/gustavo-mmh/translate_document_challenge.git

2. Navegue até o diretório do projeto:
    ```bash
    cd translate_document_challenge

3. Instale as dependências:
    ```bash
    pip install -r requirements.txt

4. Crie um arquivo .env com as configurações do seu Azure:
    # Exemplo de arquivo .env
    ```bash
    AZURE_OPENAI_KEY:  
    AZURE_DEPLOYMENT_NAME:
    AZURE_MODEL_NAME:
    AZURE_API_VERSION:
    AZURE_ENDPOINT:

5. Execute o script principal:
    ```bash
    python main.py

## Contribuição
1. Faça um fork do projeto.

2. Crie uma nova branch:
    ```bash
    git checkout -b minha-nova-funcionalidade

3. Faça suas alterações e commit:
    ```bash
    git commit -m 'Adiciona nova funcionalidade'

4. Envie para o branch original:
    ```bash
    git push origin minha-nova-funcionalidade

5. Faça um pull request para a branch principal.