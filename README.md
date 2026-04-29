# DATA IA - Tratativa de Nao Conformidade

Web app para conduzir tratativas de nao conformidade com apoio da OpenAI API.

## Stack

- Vite + React + TypeScript
- API serverless em `api/chat.ts`
- Deploy na Vercel

## Rodar localmente

```bash
npm install
npm run dev
```

Crie um arquivo `.env` ou `.env.local` com:

```bash
OPENAI_API_KEY=sk-proj-sua-chave
OPENAI_MODEL=gpt-4.1-mini
```

## Deploy na Vercel

1. Suba esta pasta para um repositorio Git.
2. Importe o repositorio na Vercel.
3. Configure o projeto com:
   - Framework: Vite
   - Build command: `npm run build`
   - Output directory: `dist`
4. Adicione as variaveis de ambiente:
   - `OPENAI_API_KEY`
   - `OPENAI_MODEL`

## Proximas evolucoes

- Persistencia em banco de dados.
- Login e perfis de usuario.
- Upload dos arquivos de conhecimento.
- Busca semantica/RAG nos documentos do GPT personalizado.
- Relatorio final em PDF ou DOCX.
