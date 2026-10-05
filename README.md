# CoordTech — Coordenação de Tecnologia

Sistema React + Vite preparado para deploy no Vercel.

## Matriz TDS oficial usada nos cálculos

- Módulo I — 446h: UC1 36h, UC2 96h, UC3 84h, UC4 92h, UC5 108h, UC6 30h.
- Módulo II — 253h: UC8 60h, UC9 96h, UC10 36h, UC11 36h, UC17-I PI FS 25h.
- Módulo III — 409h: UC12 96h, UC13 96h, UC14 36h, UC15 96h, UC16 60h, UC17-II PI II FS 25h.
- Módulo IV — 108h: UC7 108h.
- Total TDS: 1.216h.

A UC17 foi dividida em duas partes independentes: UC17-I (25h no Módulo II) e UC17-II (25h no Módulo III), permitindo aproveitamento, previsão de início e cálculo de encontros separadamente.
Os totais da matriz TDS são calculados diretamente a partir das UCs e não podem ser sobrescritos por dados antigos do navegador, evitando divergências.

## Executar localmente

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Vercel

Importe o projeto no Vercel. O arquivo `vercel.json` já está incluído.

## Atualização: assinaturas, Financeiro e novos cronogramas

As matrizes, cálculos, histórico, campos existentes, chaves de armazenamento e os sete links originais de CLASS_SCHEDULES foram preservados.

- O cabeçalho do parecer não mostra CoordTech. O documento fica em preto e branco, com Pedagogo(a) acima à esquerda e dois Docentes lado a lado abaixo.
- Financeiro abre a planilha APROVEITAMENTO 2026.xlsx no SharePoint pelo endereço fornecido.
- Cronogramas das turmas permite adicionar turma, curso e link. Os novos links são acrescentados aos originais e salvos no navegador. Cadastros para Todos os cursos aparecem em TDS e TIA. As permissões da planilha continuam sendo as do Excel/SharePoint.

Abra a pasta coordtechSenac-main no VS Code e execute:

```bash
npm ci
npm run dev
```

Para o deploy, execute `npm run build`. No Vercel, use Vite, build `npm run build` e pasta de saída `dist`. O ZIP inclui o build de produção e o código-fonte. Os cadastros são locais ao navegador, sem sincronização entre computadores.

## Download do parecer em PDF

Na aba Aproveitamento, use **Baixar parecer em PDF** ao lado do botão de PNG. O PDF é gerado em A4, com páginas adicionais quando necessário, preservando linhas de tabelas e as assinaturas juntas. O conteúdo é uma imagem do parecer; o texto não é selecionável. Não é necessário usar Imprimir ou Salvar como PDF do navegador.
