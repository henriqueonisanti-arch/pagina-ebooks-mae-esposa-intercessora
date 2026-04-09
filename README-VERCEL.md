# Vercel Deployment Configuration

Este projeto está pronto para deploy na Vercel. Siga as instruções abaixo para garantir que tudo funcione corretamente.

## Passos para Deploy

1. **Acesse https://vercel.com/**
2. Clique em "New Project" e conecte seu repositório do GitHub.
3. Escolha o repositório `pagina-ebooks-mae-esposa-intercessora`.
4. Vercel detecta automaticamente projetos estáticos (HTML/CSS/JS) e faz o deploy sem configuração extra.

## Configuração recomendada
- Certifique-se de que o arquivo principal seja `index.html` na raiz do projeto.
- Não é necessário configurar build se for apenas HTML/CSS/JS.
- Se quiser usar domínio próprio, configure em "Domains" na Vercel.

## Arquivos sugeridos
- `index.html` (já existe)
- Pasta `assets/` para imagens
- (Opcional) Adicione um arquivo `vercel.json` para configurações avançadas.

## Exemplo de `vercel.json` (opcional)

```
{
  "cleanUrls": true,
  "rewrites": [
    { "source": "/", "destination": "/index.html" }
  ]
}
```

---

Pronto! Basta conectar o repositório na Vercel e publicar.