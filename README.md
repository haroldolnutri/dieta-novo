# NutriPlanner @hlnutri

Aplicação React/Vite para montagem de planos alimentares, pacientes, banco de alimentos, substituições com equivalência calórica e exportação via impressão para PDF.

## Rodar localmente

```bash
npm install
npm run dev
```

## Build de produção

```bash
npm run build
```

## Estrutura

- `src/data`: alimentos, pacientes e modelos iniciais
- `src/utils`: cálculos nutricionais e formatação
- `src/components/ui`: componentes visuais reutilizáveis
- `src/components/diet`: componentes do editor de dieta e equivalências
- `src/components/layout`: navegação
- `src/views`: telas principais e impressão/PDF
- `src/App.jsx`: estado principal e roteamento interno

## GitHub

Crie um repositório vazio e execute:

```bash
git init
git add .
git commit -m "feat: estrutura inicial do NutriPlanner"
git branch -M main
git remote add origin SEU_REPOSITORIO
git push -u origin main
```

## Observação sobre PDF

O botão de exportação usa a impressão nativa do navegador com layout A4. Na janela de impressão, selecione **Salvar como PDF**.

## Arquivo original

O JSX recebido foi mantido em `legacy/NutriPlanner_original.jsx` somente como referência. O app ativo usa a estrutura modular em `src/`.
