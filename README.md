---

# PDF Text Extraction using Gemini PRO

<!-- Se tiver um logo, coloque o link aqui [Gemini PRO Logo](link_para_logo.png)  -->

Este projeto utiliza a IA Gemini PRO para realizar extração de texto livre de arquivos PDF de forma automatizada.

## Funcionalidades

- **Extração de Texto:** Utiliza o modelo Gemini PRO para extrair texto de arquivos PDF.
- **Suporte a Diferentes Formatos:** Capaz de lidar com uma variedade de layouts e formatos de PDF.
- **Facilidade de Uso:** Integração simplificada para extração rápida e eficiente.

## Como Usar

### Pré-requisitos

- Anaconda
- Python 3.10
- Bibliotecas necessárias (listadas no arquivo `requirements.txt`)

### Instalação

1. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/gemini-pdf-text-extractor.git
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd gemini-pdf-text-extractor
   ```

3. Crie o ambiente virtual usando Anaconda:

   ```bash
   conda create -p venv python=3.10 -y
   ```

4. Ative o ambiente virtual:

   - No Windows:

     ```bash
     conda activate venv
     ```

   - No macOS/Linux:

     ```bash
     source activate venv
     ```

5. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

6. Crie um arquivo `.env` na raiz do projeto com as seguintes informações:

   ```
   GOOGLE_API_KEY = 'API_KEY'
   ```
   
   Substitua 'API_KEY' pela chave de API do Google Gemini Pro fornecida para seu projeto.

### Executar o Aplicativo

Para iniciar o aplicativo de interface gráfica com Streamlit, execute o seguinte comando no terminal:

```bash
streamlit run app.py
```

### Demonstração

![Interface do Aplicativo](https://github.com/user-attachments/assets/5e552851-30a5-4363-aa4d-0e05a6fbf970)

Na interface do aplicativo, você pode carregar arquivos PDF, fazer perguntas sobre o conteúdo dos documentos e receber respostas geradas pela IA Google Gemini Pro.

### Contribuições

Contribuições são bem-vindas! Para sugestões, melhorias ou correções, sinta-se à vontade para abrir uma issue ou enviar um pull request.

---
