# ETLProjectAPIExtract

## 📋 Descrição
Este projeto implementa um processo de ETL (Extract, Transform, Load) utilizando Python e a biblioteca Requests para extrair dados de APIs.

## 🚀 Funcionalidades
- Extração de dados via API REST
- Transformação dos dados brutos
- Carregamento em banco de dados/arquivo destino
- Logs de execução do processo

## 📦 Pré-requisitos
- Python 3.8+
- pip (gerenciador de pacotes Python)

## 🛠️ Instalação
1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/nome-do-projeto.git
cd nome-do-projeto
```

2. Crie um ambiente virtual
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. Instale as dependências
```bash
pip install -r requirements.txt
```

## 📝 Arquivo requirements.txt
```txt
requests==2.31.0
pandas==2.1.0
python-dotenv==1.0.0
```

## 🔧 Configuração
1. Crie um arquivo `.env` na raiz do projeto
2. Adicione suas variáveis de ambiente:
```txt
API_KEY=sua_chave_api
API_URL=https://api.exemplo.com
```

## 💻 Uso
```bash
python src/main.py
```

## 📁 Estrutura do Projeto
```
projeto/
│
├── src/
│   ├── __init__.py
│   ├── main.py
│   ├── extract.py
│   ├── transform.py
│   └── load.py
│
├── data/
│   ├── raw/
│   └── processed/
│
├── logs/
├── tests/
├── .env
├── .gitignore
├── requirements.txt
└── README.md
```

## 🤝 Contribuindo
1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## 📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.


