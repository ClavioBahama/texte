# Texte

Página estática de provas sociais no estilo iOS dark mode.

**Stack:** HTML

**Documentação:**
- [Issue de organização](https://github.com/ClavioBahama/texte/issues/1) — revisão e sugestões

---

## 0. Pré-requisitos

Navegador moderno (Chrome, Edge ou Firefox).
Opcional: Node.js (`npx serve`) ou Python para servir a pasta localmente.

## 1. Instalação e Execução

```powershell
npx serve .   # servir a pasta em `http://localhost:3000`
python -m http.server 8000   # alternativa sem Node.js — abrir `http://localhost:8000`
```

## 2. Estrutura do Projeto

```text
texte/
└── index.html    # único arquivo (título: Provas Sociais WhatsApp - iOS Dark Mode)
```

## 3. Funcionalidades

- Tela de provas sociais com tema escuro inspirado no iOS.
- HTML único, sem dependências externas.

## 4. Arquivos e pontos de entrada

- `index.html` — único arquivo do projeto.

## 5. Segurança

Projeto estático: nenhuma credencial identificada no repositório.

## 6. Problemas Comuns

Abrir os arquivos com `file://` pode bloquear CSS/JS em alguns navegadores — use um servidor local.
Nomes de arquivos com acentos ou espaços precisam de codificação de URL.

## 7. Observações (organização)

> Revisão realizada em 17/11/2026 durante a padronização dos repositórios, inspirada no README do FreelaMZ.
- Projeto mínimo, de arquivo único.
- Sugestão: separar CSS/JS em arquivos próprios se o projeto evoluir.

## 8. Licença

Projeto pessoal/acadêmico. Verifique a licença de templates ou bibliotecas de terceiros antes de uso comercial.

