# 🤖 Agente WhatsApp – Template (n8n)

Template **público e seguro** de workflow n8n para criação de **agentes conversacionais no WhatsApp**, com suporte a:
- Atendimento automatizado
- Contextualização de mensagens
- Integração com agenda
- Extensível para múltiplos domínios de negócio

Este repositório foi desenhado para **uso comunitário**, aprendizado e rápida adaptação.

---

## ✨ Principais Características

- 🧠 Arquitetura de **agente conversacional**
- 💬 Integração com **WhatsApp (API externa / provider)**
- 🗓️ Integração opcional com **Google Calendar**
- 📁 Integração opcional com **Google Drive**
- 🔐 **Nenhuma credencial sensível exposta**
- ♻️ Workflow reutilizável e neutro (agnóstico de domínio)
- 🧩 Nodes desativados preservados (didático)

---

## 📁 Estrutura do Repositório

```text
.
├── DW Agente Atendimento-template.json
└── README.md
```

---

## 🚀 Como Usar

### 1. Importar no n8n
1. Acesse seu painel n8n
2. Vá em **Workflows → Import**
3. Importe o arquivo:
   - `Agente WhatsApp - Template NEUTRO.json`

### 2. Configurar Variáveis / Credenciais

#### Variáveis de Ambiente (exemplo)
```env
EVOLUTION_APIKEY=
WHATSAPP_REMOTE_JID=
GOOGLE_CALENDAR_ID=
GOOGLE_DRIVE_FOLDER_ID=
```

#### Credenciais n8n
- OpenAI (ou outro LLM)
- Google Calendar (opcional)
- Google Drive (opcional)
- Provider de WhatsApp

---

## 🧠 Funcionamento do Agente

1. Recebe mensagem do WhatsApp  
2. Normaliza o contexto  
3. Processa via LLM  
4. Consulta agenda (opcional)  
5. Retorna resposta ao usuário  

Arquitetura modular e extensível.

---

## 🛠️ Casos de Uso

- Atendimento ao cliente
- Agendamentos
- Suporte
- Vendas
- Educação
- Agentes internos

---

## 📜 Licença

MIT License

---

## 🤝 Contribuições

Pull requests são bem-vindos.

---

## 🧠 Autor

Rodrigo Robledo • DoctorWeb (DW AI)
