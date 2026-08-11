# 📞 Ramais RealTime

Sistema interno de consulta de ramais, organizado por departamento, com busca por nome. A lista é atualizada em tempo real via WebSocket, sem necessidade de recarregar a página.



## ✨ Funcionalidades

- Consulta de ramais por colaborador, departamento ou ramal
- Busca rápida por nome, departamento ou número
- Atualização automática em tempo real (WebSocket)
- Organização visual por setor

## 🛠 Tecnologias

- **Backend:** Python (Flask)
- **Frontend:** HTML, CSS, JavaScript
- **Comunicação em tempo real:** WebSocket

## 📁 Estrutura do projeto

```
ramais-realtime/
├── templates/
│   └── index.html        # Página principal
├── static/
│   ├── style.css          # Estilos
│   └── app.js              # Lógica frontend + WebSocket
├── app.py                     # Aplicação Flask principal
├── requirements.txt      # Dependências Python
├── .env.example              # Exemplo de variáveis de ambiente
└── docs/                       # Documentação adicional
```

## 🚀 Como rodar localmente

> ⚠️ Este projeto se conecta a um banco de dados interno da empresa. Para rodar localmente, é necessário configurar suas próprias variáveis de ambiente e fonte de dados.

```bash
# Clone o repositório
git clone https://github.com/ArthurMenegasso/RamaisRealTime.git
cd RamaisRealTime

# Crie um ambiente virtual (opcional, recomendado)
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt

# Configure as variáveis de ambiente
cp .env.example .env
# edite o .env com suas próprias configurações

# Execute a aplicação
python app.py
```

A aplicação estará disponível em `http://localhost:5000` (ou na porta configurada).

## 📌 Status

✅ Projeto finalizado e em uso interno.

## 📄 Licença

Este projeto foi desenvolvido no contexto de trabalho para a **HBR Aviação** e seus direitos pertencem à empresa. Disponibilizado aqui apenas para fins de portfólio/demonstração técnica.

## 👤 Autor

**Arthur Menegasso**
[LinkedIn](#) · [GitHub](https://github.com/ArthurMenegasso)
