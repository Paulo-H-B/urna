# Urna Eletrônica - Simulador de Votação


## 📋 Descrição

Simulador interativo de urna eletrônica brasileira desenvolvido em HTML, CSS e JavaScript. O projeto replica fielmente a experiência de votação eletrônica, permitindo aos usuários simular o processo de eleição para os cargos de Governador e Presidente, com candidatos fictícios e interface similar à urna eletrônica oficial.


## ✨ Funcionalidades

- *Interface realista de urna eletrônica*: Design visual semelhante ao equipamento oficial
- *Sistema de votação completo*: Votação sequencial para Governador e Presidente
- *Múltiplas opções de voto*: Voto nominal, branco e nulo
- *Validação de candidatos*: Verificação automática do número digitado
- *Exibição de informações*: Foto, nome, número, partido e vice do candidato
- *Contabilização de votos*: Sistema de armazenamento local (localStorage) para persistência dos dados
- *Resultados em tempo real*: Visualização completa dos votos após conclusão
- *Função de reset*: Botão para reiniciar a contagem de votos
- *Design responsivo*: Adaptável para dispositivos móveis e desktop


## 🚀 Tecnologias Utilizadas

- *HTML5*: Estruturação das páginas
- *CSS3*: Estilização e responsividade
- *JavaScript (ES6)*: Lógica de votação e manipulação do DOM
- *LocalStorage API*: Persistência de dados dos votos


## 📦 Estrutura do Projeto


urna/ <br>
├── index.html             # Página inicial <br>
├── simulacao.html         # Interface da urna eletrônica <br>
├── candidatos.html        # Lista de candidatos <br>
├── instrucoes.html        # Instruções de uso <br>
├── style.css              # Estilos da página inicial <br>
├── simulacao.css          # Estilos da urna <br>
├── candidatos.css         # Estilos da lista de candidatos <br>
├── instrucoes.css         # Estilos das instruções <br>
├── simulacao.js           # Lógica de votação <br>
└── img/                   # Imagens dos candidatos e logos <br>



## 💻 Como Usar

1. Abra o arquivo index.html em um navegador web moderno
2. Clique em *"Iniciar Votação"* para começar a simulação
3. Digite o número do candidato usando o teclado numérico na tela
4. Utilize os botões:
   - *BRANCO*: Para votar em branco
   - *CORRIGE*: Para corrigir o voto antes de confirmar
   - *CONFIRMA*: Para confirmar o voto
5. Vote para Governador primeiro, depois para Presidente
6. Visualize os resultados ao final da votação
7. Use *"Reiniciar Votos"* para zerar a contagem


## 🎮 Candidatos Disponíveis

### Governador
- *72* - The Pebble (PP) / Vice: The Rock
- *10* - Ben 10 (PH) / Vice: Gwen
- *12* - Serjão (PATC) / Vice: Onça
- *18* - Alanzoka (PS) / Vice: Casemiro

### Presidente
- *22* - Batman (PH) / Vice: Superman
- *13* - Mario (PS) / Vice: Luigi


## 🎯 Objetivo do Projeto

Projeto educacional desenvolvido durante o ensino médio com o objetivo de:
- Ensinar o processo eleitoral brasileiro de forma interativa
- Demonstrar habilidades em desenvolvimento web front-end
- Aplicar conceitos de JavaScript para manipulação de DOM e armazenamento local
- Criar uma interface de usuário intuitiva e responsiva


## 🔧 Funcionalidades Técnicas

- *Sistema de validação*: Verifica números de candidatos válidos
- *Gerenciamento de estado*: Controle de etapas (governador → presidente → resultados)
- *Persistência de dados*: Votos salvos em localStorage
- *Feedback visual*: Mensagens para votos nulos e brancos
- *Responsividade*: Layout adaptável usando media queries


## 📱 Responsividade

O projeto é totalmente responsivo e se adapta a:
- Desktop (800px+)
- Tablet (768px - 800px)
- Mobile (até 768px)
