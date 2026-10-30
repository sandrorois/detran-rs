# Detran RS

Landing page estatica de demonstracao usando uma unica imagem JPG como conteudo da pagina.

## Estrutura

```text
detran-rs/
├── index.html
├── styles.css
├── assets/
│   └── detran-rs-img.jpg
└── README.md
```

## Imagem

Imagem original usada pela pagina:

```text
assets/detran-rs-img.jpg
```

O HTML exibe a imagem em 100% da largura disponivel, preservando a proporcao original e permitindo rolagem vertical natural. Os atributos `width` e `height` usam as dimensoes reais da imagem para reduzir mudancas de layout durante o carregamento.

## Teste local

Como o projeto e estatico, basta abrir `index.html` no navegador. Se preferir servir por HTTP:

```bash
npx serve .
```

## Publicacao no GitHub

Inicialize o Git, crie o commit e envie para um repositorio GitHub vazio:

```bash
git init
git add .
git commit -m "Create static Detran RS landing page"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
git push -u origin main
```

## Deploy na Vercel

1. Acesse https://vercel.com/new.
2. Importe o repositorio GitHub.
3. Mantenha o framework como `Other` ou `Static`.
4. Deixe o comando de build vazio.
5. Deixe o diretorio de saida como raiz do projeto.
6. Clique em `Deploy`.

A cada novo push na branch `main`, a Vercel fara o deploy automatico.
