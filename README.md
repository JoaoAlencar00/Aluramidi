# Alura MIDI

Instrumento de percussão no navegador desenvolvido para praticar JavaScript, eventos e interação com elementos de áudio.

## Recursos

- Nove botões associados a arquivos de som.
- Reprodução ao clicar nos botões.
- Estado visual de tecla ativa ao usar Espaço ou Enter com o botão em foco.

## Tecnologias e aprendizados

HTML5, CSS3 e JavaScript. O projeto explora seletores do DOM, funções, laços de repetição, template strings e tratamento de eventos de mouse e teclado.

## Como executar

Clone ou baixe o repositório e abra `index.html` em um navegador. Clique nos botões para tocar os sons. Para navegar pelo teclado, use Tab e acione o botão em foco com Enter ou Espaço.

O projeto não exige instalação de dependências ou etapa de build.

## Estrutura

- `index.html`: teclado e elementos de áudio.
- `main.js`: associação entre botões, sons e eventos.
- `css/`: estilos.
- `sounds/`: arquivos de áudio.
- `images/`: imagem do projeto.

## Estado do projeto

Exercício de aprendizagem. A função `tocaSom` ainda pode ser aprimorada para validar o elemento antes de chamar `play()` e tratar o retorno assíncrono da reprodução.

Projeto educacional baseado no Alura MIDI, da Alura.
