# Lista de Exercícios — Programação Web 2026.2

Respostas das 28 questões. Todo o código roda direto no navegador, sem bibliotecas externas e sem internet: basta abrir o `index.html` de cada pasta.

## Estrutura

```
respostas-programacao-web/
├── README.md
├── parte-1-multipla-escolha/
│   └── respostas-questoes-1-a-17.docx    alternativa marcada com (X) + justificativa
├── parte-2-codigo/
│   ├── questao-18-e-20-blog/              Q18 = index.html | Q20 = style.css
│   ├── questao-19-22-e-25-formulario/     Q19 = index.html | Q22 = style.css | Q25 = script.js
│   ├── questao-21-cards/                  index.html, style.css e img/ (imagens SVG locais)
│   ├── questao-23-primos/                 resultado no console
│   ├── questao-24-contador/
│   ├── questao-26-imc/
│   └── questao-27-produtos/               resultado na página e no console
└── parte-3-desafio-integrador/
    └── questao-28-lista-de-tarefas/
```

## Observações

- As questões 18 e 20 ficam na mesma pasta porque a 20 é o CSS da página da 18. Pelo mesmo motivo, 19, 22 e 25 (HTML, CSS e validação do mesmo formulário) ficam juntas.
- Questões 23 e 27: abra o console do navegador (F12, aba Console). A 27 também mostra os resultados na própria página.
- Questões 23 a 26 usam apenas JavaScript clássico: `var`, `function`, laços `for` e concatenação com `+`.
- Questão 27 usa apenas `let`/`const` e arrow functions, com `map`, `filter` e `reduce`, sem `var` e sem laços `for`.
- Questão 25: além dos erros pedidos (nome com menos de 3 caracteres e termos não aceitos), o e-mail também é conferido. A validação nativa do navegador é desligada para que as mensagens personalizadas apareçam abaixo dos campos, então o campo obrigatório de e-mail precisa ser verificado pelo script.
- Questão 26: os campos aceitam vírgula ou ponto como separador decimal (1,75 ou 1.75).
- Questão 28 (bônus): as tarefas ficam salvas no `localStorage` e continuam na lista ao reabrir a página. O layout também tem tema escuro automático.
