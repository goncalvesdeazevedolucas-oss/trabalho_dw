# Relatório de Aprendizagem: Publicando uma Página Web Estática no GitHub Pages

**Aluno:** Lucas Gonçalves de Azevedo
**Turma:** 1f, Técnico Integrado em Informática para Internet, IFC Campus Concórdia
**Disciplina:** Desenvolvimento Web I
**Professor:** Hewerton Enes de Oliveira
**Site:**
**Repositório:**

## 1. Introdução

Neste trabalho publiquei uma página web estática na internet usando GitHub Pages. Escolhi como tema os jogos que eu jogo (Blox Fruits, Fisch, The Binding of Isaac: Repentance+ e Minecraft), porque é um assunto que eu conheço e que me motiva. O tema não tem relação com o Projeto Integrador.

O site usa só HTML e CSS escritos por mim, sem JavaScript, sem framework e sem tema pronto. Não usei Jekyll nem Hugo, então não estou concorrendo ao bônus.

## 2. Passo a passo

1. **Leitura da especificação.** Li o PDF inteiro antes de começar e anotei os requisitos: só HTML e CSS, repositório público, commits organizados, README e relatório.
2. **Pesquisa na documentação oficial.** Comecei pela documentação do GitHub Pages (docs.github.com/pages), depois vi o que é Markdown e o que fazem os comandos `git init`, `git add`, `git commit` e `git push`.
3. **Escolha do tema e planejamento.** Defini as seções da página (Sobre, Jogos e Resumo) e a estrutura de arquivos: `index.html` e `style.css` na raiz do repositório.
4. **Conta e repositório no GitHub.** Usei minha conta do GitHub e criei um repositório público, sem tema e sem template.
5. **Criação do HTML.** Escrevi o `index.html` com tags semânticas (`header`, `nav`, `main`, `section` e `article`), uma grade de cartões e uma tabela de resumo.
6. **Criação do CSS.** Escrevi o `style.css` com variáveis CSS para as cores, `grid` para os cartões, `flexbox` no menu, efeitos de `hover` e uma regra `@media` para telas pequenas.
7. **Git local.** Iniciei o repositório com `git init` e fiz os commits em etapas, separando cada mudança por sentido: estrutura do HTML, conteúdo, estilo, README e relatório.
8. **Envio ao GitHub.** Conectei o repositório local ao remoto com `git remote add origin` e enviei com `git push -u origin main`.
9. **Ativação do GitHub Pages.** No repositório, fui em *Settings > Pages*, escolhi a branch `main` e a pasta `/ (root)` como fonte e salvei.
10. **Teste.** Depois de alguns minutos abri o link em uma aba anônima e em outro navegador para confirmar que o site abria para qualquer pessoa.
11. **Checklist final.** Conferi todos os itens do checklist do anexo da especificação antes de entregar.

### Commits realizados

| Commit | O que mudou |
|---|---|
| `Cria estrutura inicial do index.html` | esqueleto do HTML, com cabeçalho, seções e rodapé |
| `Adiciona conteúdo dos jogos e tabela de resumo` | cartões dos jogos e tabela |
| `Adiciona folha de estilo style.css` | layout, cores e responsividade |
| `Adiciona README.md` | descrição do projeto |
| `Adiciona relatório de aprendizagem` | este arquivo |

## 3. Ferramentas usadas e por quê

- **HTML e CSS:** exigidos pela especificação e vistos nos Encontros 1 e 2. Dão conta de uma página estática sem precisar de mais nada.
- **Editor de código (VS Code):** para escrever e organizar os arquivos, com destaque de sintaxe e visualização da estrutura de pastas.
- **Navegador e ferramentas de desenvolvedor (F12):** para testar o layout, inspecionar elementos e simular telas de celular.
- **Git:** para versionar o código. Cada commit guarda um estado do projeto, então é possível voltar atrás se algo der errado.
- **GitHub:** para guardar o repositório na nuvem. É também a plataforma exigida pelo trabalho.
- **GitHub Pages:** para hospedar o site de graça, direto do repositório, sem servidor próprio.
- **Markdown:** para escrever o README e este relatório. É simples e o GitHub mostra formatado automaticamente.
- **MDN Web Docs e documentação do GitHub:** como fontes principais de pesquisa, por serem oficiais.

## 4. Conceitos novos que aprendi

- **Site estático:** um site formado só por arquivos prontos (HTML, CSS, imagens) que o servidor entrega como estão, sem processar nada no servidor.
- **Hospedagem:** para o site ser aberto por qualquer pessoa, os arquivos precisam estar em um servidor ligado à internet. O GitHub Pages faz esse papel.
- **Git:** um sistema de controle de versão. Aprendi o fluxo `git add` (escolhe o que entra), `git commit` (registra uma versão com mensagem) e `git push` (envia ao GitHub).
- **Repositório local e remoto:** o local fica no meu computador e o remoto fica no GitHub. O `git push` sincroniza os dois.
- **Branch:** uma linha de desenvolvimento. O GitHub Pages publica a partir de uma branch escolhida, no meu caso a `main`.
- **Mensagens de commit claras:** descrevem o que mudou, e mudanças diferentes vão em commits diferentes.
- **Markdown:** uma sintaxe simples de marcação (`#` para títulos, `-` para listas, `**` para negrito). O `README.md` é a página de apresentação do repositório.
- **`index.html`:** o nome do arquivo que o servidor abre por padrão. Se ele não existir na raiz, o site não aparece.
- **URL do GitHub Pages:** segue o formato `usuario.github.io/repositorio`, e o site só fica no ar depois de alguns minutos da ativação.
- **CSS moderno:** variáveis CSS (`--cor`), `grid`, `flexbox` e media queries para o layout se adaptar ao celular.

## 5. Dificuldades

- No começo o link do site dava erro 404. Aprendi que o GitHub Pages leva alguns minutos para publicar depois de ativado e que o `index.html` precisa estar na raiz do repositório.
- Precisei entender a diferença entre `git add`, `git commit` e `git push`, porque no início achei que o `commit` já enviava o código ao GitHub.
- Ajustar o layout para telas pequenas exigiu testar com o modo responsivo do navegador.

## 6. Conclusão

O trabalho me mostrou o caminho completo de uma página web, desde o código até um link público que qualquer pessoa abre. Usar o Git desde o começo me ajudou a manter o projeto organizado, e o GitHub Pages mostrou que publicar um site simples é bem mais acessível do que eu imaginava.
