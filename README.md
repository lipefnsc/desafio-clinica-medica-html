# Site de Clínica Médica (Desafio HTML - DIO)

Projeto desenvolvido para o desafio da trilha **HTML (Módulo 2)**, com o objetivo de criar um site “quase completo” de uma **clínica médica**, aplicando os conteúdos vistos em aula: **formulários, textos, mídias (banners), tabelas** e navegação entre páginas.

## Páginas do site

Todas as páginas seguem o mesmo padrão de layout: **Menu (navegação)** + **Header (banner)** + **Content (conteúdo da página)** + **Footer (contato da clínica)**, com estilos centralizados em um único CSS.

- **Página principal (`index.html`)**
  - Banner no header + texto de apresentação da clínica.
- **Sobre a clínica (`sobre.html`)**
  - Banner diferente + texto explicando missão/estrutura/atendimento.
- **Horário de atendimento (`horarios.html`)**
  - Banner diferente + texto dos serviços + **tabela** com horários por dia.
- **Contato (`contato.html`)**
  - Banner diferente + telefones e endereço + **Google Maps (iframe)** + **formulário** com botões de enviar e limpar.

## Tecnologias utilizadas

- **HTML5** (estrutura do site)
- **CSS3** (estilização geral, tabela e formulário)

## Estrutura sugerida do projeto

```txt
/
├─ index.html
├─ sobre.html
├─ horarios.html
├─ contato.html
├─ css/
│  └─ style.css
└─ img/
   ├─ banner-paginaprincipal.jpg
   ├─ banner-sobre.jpg
   ├─ banner-horarios.jpg
   └─ banner-contato.jpg
```

## Como executar

1. Baixe/clone o projeto.
2. Abra o arquivo `index.html` no navegador (duplo clique), **ou**
3. Use a extensão **Live Server** no VS Code para recarregar automaticamente enquanto edita.