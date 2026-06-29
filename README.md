<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1F0D,100:00FF41&height=180&section=header&text=Willkerson%20Barcelar&fontSize=36&fontColor=00FF41&fontAlignY=35&desc=Developer%20%7C%20Founder%20%7C%20Builder&descSize=14&descAlignY=55" width="100%">

### `$ whoami` → Dev que constrói o que precisa e vende o que constrói

**Automação · ERP · E-commerce · Sistemas que trabalham enquanto você dorme**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/willkerson-barcelar-3411b2151)
[![GitHub](https://img.shields.io/badge/GitHub-161b22?style=for-the-badge&logo=github&logoColor=00FF41)](https://github.com/Willkerson)

---

`Playwright` · `GitHub Actions` · `Node.js` · `ERP Automation` · `E-commerce` · `Python`

</div>

---

## 📊 Overview

```
┌─────────────────────────────────────────────────────────────────┐
│  WILLKERSON BARCELAR                          São Paulo, BR      │
│  ─────────────────────────────────────────────────────────────  │
│  Founder @ CIA das Embalagens                                   │
│  Dev por necessidade → Dev por escolha                          │
│                                                                  │
│  Construo sistemas que automatizam o que seria feito à mão:     │
│  cadastro de produtos, movimentação de estoque, alertas,        │
│  sincronização com ERP — tudo rodando em CI/CD no GitHub.       │
└─────────────────────────────────────────────────────────────────┘
```

---

## 💹 O Que Eu Faço

```
╔═══════════════════════════════════════════════════════════════════════╗
║  ⚙️  AUTOMAÇÃO & ERP                ║  🛒 E-COMMERCE & STOREFRONT      ║
║  ──────────────────────────         ║  ──────────────────────────────  ║
║  • Playwright (browser automation)  ║  • GitHub Pages como infra       ║
║  • GitHub Actions / CI-CD           ║  • PWA mobile-first              ║
║  • ConnectPlug API integration      ║  • Catálogo dinâmico via JSON    ║
║  • Cadastro e sync de produtos      ║  • Barcode scan + reconhecimento ║
╠═══════════════════════════════════════════════════════════════════════╣
║  📦 GESTÃO DE ESTOQUE               ║  🔔 ALERTAS & NOTIFICAÇÕES       ║
║  ─────────────────────              ║  ───────────────────────────     ║
║  • Painel admin dark mobile         ║  • WhatsApp via CallMeBot        ║
║  • Movimentação via queue/fila      ║  • Alertas de estoque zerado     ║
║  • Ocultar itens sem estoque        ║  • Workflow chaining no Actions  ║
║  • Imagens por produto (JSON)       ║  • Screenshots por execução      ║
╚═══════════════════════════════════════════════════════════════════════╝
```

---

## 🛠️ Stack

<div align="center">

### Automação & Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

### Frontend & Mobile
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)

### Integração & Dados
![REST API](https://img.shields.io/badge/REST_API-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)
![ConnectPlug](https://img.shields.io/badge/ConnectPlug-ERP-FF6B00?style=for-the-badge)
![WhatsApp](https://img.shields.io/badge/WhatsApp_API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)

</div>

---

## 📁 Repositórios

| Projeto | Descrição | Stack |
|:--------|:----------|:------|
| [🛍️ Web.embalagens](https://github.com/Willkerson/Web.embalagens) | Storefront + painel admin de estoque da CIA das Embalagens | HTML · JS · PWA · GitHub Pages |
| 🔒 Automacao-ConnectPlug | Suite de automação do ERP: cadastro, sync, alertas, movimentação | Node.js · Playwright · Actions |

> 🔒 *Repositório de automação privado — arquitetura modular com scripts independentes orquestrados por GitHub Actions*

---

## 🏗️ Arquitetura (CIA das Embalagens)

```
                        GITHUB ACTIONS
                       ┌──────────────┐
          trigger      │              │      trigger
    ┌────────────────► │  cadastrar   │ ──────────────────┐
    │                  │    .yml      │                    │
    │                  └──────────────┘                    │
    │                                                      ▼
┌───┴──────────┐       ┌──────────────┐       ┌─────────────────────┐
│  admin-      │       │  movimentar  │       │     atualizar.yml   │
│  estoque     ├──────►│    .yml      ├──────►│  exportar.js        │
│  .html       │       │              │       │  ocultar.js         │
│  (browser)   │       └──────────────┘       │  alertar.js         │
└──────────────┘                              └─────────────────────┘
       │                                               │
       │  GitHub API                          ConnectPlug API + WhatsApp
       ▼
  fila/movimentacao.json
  produto-imagens.json
```

---

## 📈 Filosofia

```javascript
const willkerson = {
  mentalidade: "Se tem que fazer todo dia → automatiza",
  abordagem:   "Produto real > código perfeito",
  stack:       "O que resolve o problema agora",
  negócio:     "CIA das Embalagens — SP",
  próximo:     ["scanner.html + ML", "dashboard financeiro", "..."],
};
```

---

<div align="center">

### 📬 Vamos Conversar?

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/willkerson-barcelar-3411b2151)

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1F0D,100:00FF41&height=100&section=footer" width="100%">

</div>
