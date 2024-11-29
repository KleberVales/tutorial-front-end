# Tutorial front-end

### HTML: Estrutura e Conteúdo 

1. Introdução ao HTML
   - O que é HTML?
   - Estrutura básica de um documento HTML.
   - Tags essenciais: < html >, < head >, < body >.
  
2. Elementos e Tags Comuns
   - Títulos: < h1 > a < h6 >.
   - Parágrafos: < p >.
   - Links: < a >.
   - Imagens: < img >.
   - Listas:
     * Não ordenadas: < ul > e < li >.
     * Ordenadas: < ol > e < li >.
    
3. Formatação de Texto
   - Negrito: < strong >.
   - Itálico: < em >.
   - Linhas horizontais: < hr >.
   - Quebras de linha: < br >.
  
4. Formulários
   - Campos de entrada: < input > (texto, senha, email, etc.).
   - Botões: < button >.
   - Textarea: < textarea >.
   - Seleções: < select > e < option >.
   - Rádios e checkboxes.
  
5. Tabelas
   - Estrutura básica: < table >, < tr >, < td >, < th >.
   - Atributos: bordas, colspan, rowspan.
  
6. Semântica no HTML
   - Tags semânticas: < header >, < footer >, < main >, < section >, < article >, < aside >.
   - Importância do uso semântico para SEO e acessibilidade.
  
7. Links e Navegação
   - Links absolutos e relativos.
   - Navegação entre páginas e âncoras

### CSS: Estrutura e Conteúdo 
1. Fundamentos do CSS
   - O que é CSS e como funciona?
     * Cascading e herança.
     * Como o navegador processa CSS.
    
   - Métodos de Aplicação do CSS:
     * Inline, interno (<style> no HTML) e externo (.css).
    
   - Seletores:
     * Básicos (tags, classes, IDs).
     * Avançados (atributos, combinadores, pseudo-classes, pseudo-elementos).
    
   - Box Model:
     * Margens, preenchimentos, bordas e conteúdo.
     * Controle de espaço com margin e padding.

2. Layouts e Posicionamento
   - Display:
     * block, inline, inline-block, none.

   - Posicionamento:
     * static, relative, absolute, fixed, sticky.

   - Modelos de Layout:
     * Flexbox:\
       Eixos principal e transversal.\
       Propriedades como justify-content, align-items.

     * CSS Grid:\
       Configuração de grades (grid-template-columns, grid-template-rows).\
       Alinhamento e distribuição de itens.

   - Layouts Responsivos:
     * Media Queries (@media).
     * Tamanhos relativos (em, rem, %, vw, vh).
    
3. Estilização Avançada
   - Cores e Fundos:
     * Gradientes (linear-gradient, radial-gradient).
     * Transparência com rgba, hsla.
    
   - Tipografia:
     * Propriedades como font-size, line-height, letter-spacing.
     * Fontes customizadas com @font-face.
    
   - Animações e Transições:
     * transition (duração, atraso, timing-function).
     * Criando animações com @keyframes.
    
   - Efeitos Avançados:
     * Sombras (box-shadow, text-shadow).
     * Clip-path para criar formas customizadas.
     * Filtros (filter, blur, brightness).
    
 4. Design Responsivo e Mobile-First
    - Media Queries Avançadas:
      * Breakpoints para dispositivos móveis, tablets e desktops.
     
    - Unidades e Funções Modernas:
      * Uso de clamp(), min(), max() para tamanhos dinâmicos.
      * Propriedades relativas como calc().
     
    - Frameworks CSS:
      * Bootstrap, Tailwind CSS ou Foundation para acelerar o desenvolvimento.

### JavaScript 

1. Fundamentos do JavaScript
   - Sintaxe básica (variáveis, operadores, tipos de dados).
   - Estruturas de controle (if/else, switch, loops).
   - Funções (declaração, expressão, arrow functions).
   - Arrays e objetos (manipulação e métodos comuns).
   - Manipulação de strings e números.


2. Conceitos Avançados da Linguagem
   - Escopo e hoisting.
   - Event loop, call stack e assincronismo (promises, async/await).
   - Closures.
   - Manipulação de datas (Date).
   - Modularização (import/export).
   - Classes e herança.

3. Manipulação do DOM (Document Object Model)
   - Seleção de elementos (querySelector, getElementById, etc.).
   - Manipulação de atributos, classes e estilos.
   - Criação e remoção de elementos dinamicamente.
   - Eventos (addEventListener, bubbling e delegation).


4. Trabalhando com APIs
    - Fetch API (GET, POST, PUT, DELETE).
    - Manipulação de respostas JSON.
    - Gerenciamento de erros (try/catch).
    - APIs do navegador (geolocalização, localStorage, etc.).


5. Integração com HTML e CSS
    - Manipulação de formulários e validação.
    - Alteração dinâmica de classes e estilos.
    - Trabalhar com animações e transições CSS via JavaScript.


6. Ferramentas e Bibliotecas
     - Introdução ao uso de frameworks (como React ou Vue.js).
     - Uso de bibliotecas utilitárias (Lodash, Axios).
     - Gerenciamento de pacotes com npm/yarn.


7. Controle de Versão e Debugging
     - Depuração no navegador (dev tools).
     - Controle de versão com Git.

### React

1. Fundamentos do React
   - JSX (JavaScript XML): Sintaxe para escrever componentes.
   - Componentes: Função e classe, componentes funcionais e baseados em classe.
   - Props: Como passar dados entre componentes.
   - State: Gerenciamento de estado local em componentes.
   - Eventos: Como lidar com eventos (ex: onClick, onChange).
  
2. Ciclo de Vida dos Componentes
   - componentDidMount() e outros métodos de ciclo de vida (para componentes de classe).
   - useEffect: Equivalente funcional para lidar com efeitos colaterais em componentes funcionais.
  
3. Hooks
   - useState: Para gerenciar o estado em componentes funcionais.
   - useEffect: Para lidar com efeitos colaterais em componentes funcionais.
   - useContext: Para usar contexto de forma mais fácil.
   - useRef: Para acessar elementos diretamente ou manter valores imutáveis.
   - useMemo e useCallback: Para otimizar desempenho e evitar re-renderizações desnecessárias.
  
4. Gerenciamento de Estado
   - Context API: Para compartilhar dados entre componentes sem a necessidade de passar props.
   - Redux (ou outra solução): Para gerenciar o estado global da aplicação.

5. React Router
   - Roteamento: Navegação entre páginas dentro de uma aplicação React (ex: BrowserRouter, Route, Link).
   - Parâmetros de URL e navegação programática: Usar links dinâmicos e redirecionamentos.
  
6. Forms em React
   - Controle de formulários: Lidando com inputs controlados e não controlados.
   - Validação de formulário: Como fazer a validação do formulário e tratar erros.
  
7. Renderização Condicional
   - Técnicas para renderizar componentes ou partes da UI com base no estado ou dados.
  
8. Lidando com Dados
   - Fetching de dados: Usando fetch, axios, ou outras bibliotecas para buscar dados de APIs.
   - Promise e Async/Await para lidar com chamadas assíncronas.
  
9. Estilos em React
    - CSS Modules: Estilos locais para componentes.
    - Styled Components: Bibliotecas como styled-components para usar CSS dentro do JavaScript.
    - CSS-in-JS: Abordagens para estilos dinâmicos e reutilizáveis.



     



  

     
