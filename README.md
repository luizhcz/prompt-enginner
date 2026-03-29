# Prompt Engineer

Ferramenta visual para edição e comparação de prompts JSON.

**Acesso:** https://luizhcz.github.io/prompt-enginner/

## Funcionalidades

- **Tela Editor** — visualização lado a lado do prompt original (esquerda) e editável (direita), com diff em tempo real (vermelho = removido, verde = adicionado)
- **Tela Diferenças** — visão consolidada de todas as alterações feitas, com download do JSON modificado
- **Busca** — Ctrl+F para buscar texto nos dois painéis
- **Scroll travado** — sincroniza a rolagem dos dois painéis pela proporção do documento

## Uso local

```bash
cd prompt-enginner
python3 -m http.server 8888
# abre http://localhost:8888
```

## Atualizar o site

```bash
git add -A && git commit -m "descrição" && git push
```
