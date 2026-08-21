# NutriPlanner @hlnutri

Aplicação React/Vite para criar planos alimentares, gerenciar pacientes, consultar alimentos, calcular substituições equivalentes e imprimir dietas em PDF.

## Rodar no computador

Requer Node.js 20 ou superior.

```bash
npm install
npm run dev
```

Abra o endereço exibido no terminal.

## Gerar a versão de produção

```bash
npm run build
npm run preview
```

Os arquivos otimizados são gerados na pasta `dist`.

## Publicar no GitHub Pages

O projeto usa caminhos relativos (`base: "./"`), portanto o conteúdo da pasta `dist` também pode ser publicado em hospedagens estáticas.

## Observação

Os dados permanecem no estado local da página durante o uso. Esta versão não possui servidor, banco de dados ou autenticação.
