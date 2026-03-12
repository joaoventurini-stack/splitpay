# SplitPay — Separador de Comprovantes PDF

Site estático para separar PDFs de comprovantes de pagamento em arquivos individuais, com nomeação automática via IA (Claude).

## ✨ Funcionalidades

- Arraste e solte PDFs com múltiplos comprovantes
- **Modo Automático (IA):** usa Claude para extrair pagador, recebedor e data de cada página
- **Modo Manual:** numeração sequencial com prefixo customizável
- Download individual ou ZIP com todos os arquivos
- Relatório detalhado de processamento
- 100% no navegador — nenhum arquivo sai do seu computador

## 🚀 Deploy no Vercel (sem instalar nada)

### Opção 1 — Via GitHub + Vercel (recomendado)

1. Faça fork ou crie um repositório no GitHub com estes arquivos
2. Acesse [vercel.com](https://vercel.com) e faça login com sua conta GitHub
3. Clique em **"Add New Project"** → selecione o repositório
4. Clique em **Deploy** — pronto!

### Opção 2 — Vercel CLI (opcional)

```bash
npx vercel --prod
```

## 🔑 Chave de API (modo automático)

Para usar a extração automática de dados, você precisa de uma chave da API do Claude:

1. Acesse [console.anthropic.com](https://console.anthropic.com)
2. Crie uma chave em **API Keys**
3. Cole a chave no campo do site antes de processar

> A chave fica apenas no seu navegador e nunca é enviada a terceiros.

## 📁 Estrutura

```
index.html   — aplicação completa (HTML + CSS + JS)
vercel.json  — configuração de deploy
README.md    — este arquivo
```
