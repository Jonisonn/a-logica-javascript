# Objeto de Aprendizagem: Lógica de Programação em JavaScript

## Sobre o Projeto
Este repositório contém um Objeto de Aprendizagem (OA) interativo desenvolvido como exercício prático. [cite_start]O OA é um recurso digital suplementar [cite: 10] focado no ensino de fundamentos e lógica de programação em JavaScript, estruturado no formato de "completar lacunas" (Fill in the Blanks) e resolução de problemas estruturados.

🔗 **[Acessar o Objeto de Aprendizagem](https://jonisonn.github.io/a-logica-javascript/)**

## Justificativa Pedagógica e Design Instrucional

[cite_start]O desenvolvimento deste OA foi fundamentado nos princípios de design de materiais pedagógicos [cite: 48][cite_start], atendendo aos dois elementos essenciais: objetivos claros e metodologia definida[cite: 24, 25]. 

A arquitetura do projeto respeita as características básicas de um bom OA:
* [cite_start]**Alta Granulosidade (Tamanho Pequeno):** O objeto é direto, autocontido e focado em um único grande tema (Lógica JS) [cite: 29, 30][cite_start], o que potencializa sua recombinação no futuro[cite: 12].
* [cite_start]**Reusabilidade:** A separação entre o motor do jogo (JavaScript) e o banco de questões permite que o código seja facilmente adaptado para outras disciplinas[cite: 28, 71].
* [cite_start]**Interoperabilidade e Acessibilidade:** Construído exclusivamente com HTML5, CSS3 e Vanilla JavaScript, o recurso não exige instalação de plugins, rodando nativamente em diferentes navegadores e hardwares[cite: 32, 34].
* [cite_start]**Portabilidade:** Funciona de forma totalmente client-side, hospedado em uma página WWW simples[cite: 35, 40].

### Pressupostos Teóricos
[cite_start]A matriz de atividades didáticas deste OA é fortemente ancorada no **Comportamentalismo**[cite: 60]. 

[cite_start]A escolha metodológica utiliza a **instrução programada**[cite: 60], onde o aluno avança em seu próprio ritmo mediante o acerto das lacunas. [cite_start]O sistema avalia exercícios práticos em tempo real, fornecendo **feedback individual** [cite: 60] imediato a cada submissão. Para mitigar a frustração e manter o fluxo de aprendizagem contínuo, foi implementado um mecanismo de "Ver Resposta", que zera a pontuação da questão, mas apresenta a explicação do conceito e um exemplo prático para correção de rota do estudante.

## Tecnologias Utilizadas
* **HTML5:** Estruturação semântica.
* **CSS3:** Estilização da interface, responsividade e animações de modal.
* **JavaScript (ES6):** Lógica de validação, embaralhamento aleatório (sistema de sessões de 5 questões) e manipulação do DOM.
* **Web Storage API (localStorage):** Armazenamento local para retenção assíncrona do recorde máximo (High Score), promovendo engajamento sem necessidade de backend.

## Como Executar Localmente
Como a aplicação é 100% *client-side*, não há necessidade de servidor ou configuração de ambiente.
1. Clone este repositório: `git clone https://github.com/seu-usuario/seu-repositorio.git`
2. Abra a pasta do projeto.
3. Dê um clique duplo no arquivo `index.html` para executá-lo em seu navegador padrão.
