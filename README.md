# ETLProjectAPIExtract

## 📋 Descrição
Este projeto implementa um processo ETL (Extract, Transform, Load) utilizando Python. O sistema extrai dados via API usando a biblioteca Requests, realiza transformações nos dados e os carrega em um destino específico.

## 🚀 Funcionalidades
- Extração de dados via API REST
- Processamento e limpeza de dados
- Transformação do formato dos dados
- Carregamento em banco de dados/arquivo

## 🛠️ Tecnologias Utilizadas
- Python 3.x
- Requests
- Pandas
- Python-dotenv (para variáveis de ambiente)

## 📦 Estrutura do Projeto
```
projeto/
│
├── src/
│   ├── extract/
│   │   └── api_client.py
│   ├── transform/
│   │   └── data_transformer.py
│   └── load/
│       └── data_loader.py
│
├── config/
│   └── config.py
│
├── .env
├── requirements.txt
└── README.md
```

## ⚙️ Configuração do Ambiente

1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/nome-do-projeto.git
```

2. Crie um ambiente virtual
```bash
python -m venv venv
```

3. Ative o ambiente virtual
```bash
# Windows
venv\Scripts\activate

# Linux/macOS
source venv/bin/activate
```

4. Instale as dependências
```bash
pip install -r requirements.txt
```

5. Configure o arquivo .env
```env
API_KEY=sua_chave_api
API_URL=url_da_api
```

## 📝 Exemplo de Uso
```python
from src.extract.api_client import APIClient
from src.transform.data_transformer import DataTransformer
from src.load.data_loader import DataLoader

# Iniciar processo ETL
client = APIClient()
data = client.extract_data()
transformed_data = DataTransformer().transform(data)
DataLoader().load(transformed_data)
```

## 📄 Requisitos
```
requests==2.31.0
pandas==2.1.0
python-dotenv==1.0.0
```

## 🤝 Contribuindo
1. Faça o fork do projeto
2. Crie sua feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença
Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## ✒️ Autor
* **Seu Nome** - *Desenvolvimento* - [seu-usuario](https://github.com/seu-usuario)

## 📌 Observações
* Certifique-se de ter todas as credenciais necessárias para acessar a API
* Verifique a documentação da API para entender os limites de requisições
* Mantenha suas chaves de API seguras e nunca as compartilhe no repositório
```

