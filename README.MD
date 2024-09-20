# ⚡ CARDERNO DEV

_Descrição desse repositório_

Este repositório serve como uma documentação centralizada e de commits importantes de diversos projetos. Ele oferece links para buscas e acessos rápidos a commits relevantes. Duas coisas são fundamentais aqui. Primeiro, cada nova documentação deve ter o título começando com "Sessão" seguido pelo título do commit exatamente como está no projeto original. Segundo, para a "Primeira Implementação", o link deve direcionar para a primeira versão da classe ou código em questão.


## Sessão 00.00 - `00.12.01 - Pré-layout da pag-adicionar-controller`

### **Primeiro Implementação**: 
- [00.12.01 - Pré-layout da pag-adicionar-controller](https://github.com/H7-Dev/CONTROLER-FX/commit/721dc13686486a25bb487cd2b821347b57a7d60e#commitcomment-146999828)
- [link do modelo](https://github.com/H7-Dev/CONTROLER-FX/commit/721dc13686486a25bb487cd2b821347b57a7d60e#commitcomment-146999828)

### Resumo:

Este commit introduz o "Modelo A" para campos de texto, fornecendo uma estrutura modular e estilizada para inputs com suporte a ícones e mensagens de feedback. Este modelo visa padronizar a aparência e a funcionalidade dos campos de formulário na aplicação.

1. **Modelo de campo de texto**: Estrutura HTML para rótulo, input, ícones e mensagens de feedback.
2. **Estilização Flexbox**: Layout flexível e responsivo para os componentes do modelo.
3. **Interatividade dos botões**: Estilos de hover, foco e clique para botões associados ao campo de texto.
4. **Mensagens de feedback**: Área dedicada para exibir mensagens de feedback ao usuário.
5. **Integração de ícones SVG**: Suporte para ícones de entrada e pesquisa no campo de texto.



## Sessão 00.03 - `00.10.00 - Implementação da classe JS TabSwitcher ✔️✔️✔️ + 📕`


###  **Primeiro Implementação**: 

- [00.10.00 - Implementação da classe JS TabSwitcher ✔️✔️✔️ + 📕](https://github.com/H7-Dev/CONTROLER-FX/commit/86639f354655a2d41059e33e3ada9416d5b93432)
- [Link do Modeo](https://github.com/H7-Dev/CONTROLER-FX/commit/86639f354655a2d41059e33e3ada9416d5b93432#commitcomment-146948278)

### Resumo dos Recursos:

- [x] **Evento Delegado:** Utiliza evento delegado no elemento estático (geralmente `body`) para capturar cliques em botões sem a necessidade de adicionar ouvintes individuais.
- [x] **Alternância de Classes:** Gerencia a adição e remoção das classes CSS `active-tab` e `active-painel` nos botões e paineis correspondentes.
- [x] **Seleção por Atributos:** Seleciona botões e paineis pelos atributos `tab-id` e `painel-id`, respectivamente, tornando o código mais robusto e flexível.
- [x] **Configuração Flexível:** Permite configurar seletores e classes CSS através de parâmetros, facilitando a reutilização e adaptação em diferentes contextos.
- [x] **Depuração Aprimorada:** Inclui mensagens detalhadas no console (`console.log`) para facilitar a depuração e acompanhamento do fluxo de eventos.
- [x] **Documentação com JsDoc:** Contém comentários JsDoc no cabeçalho da classe para melhorar a legibilidade e auxiliar na geração de documentação automatizada.


## Sessão 00.02 - `00.06 - Classe JS DelegatedButtonClick`

###  **Primeiro Implementação**: 

- [00.06 - Classe JS DelegatedButtonClick](https://github.com/H7-Dev/CONTROLER-FX/commit/8d62af9af1b2002f110a163e56f833892cba6762)
- [Link do Modelo](https://github.com/H7-Dev/CONTROLER-FX/commit/8d62af9af1b2002f110a163e56f833892cba6762#commitcomment-146828913)


### Resumo dos Recursos:

1. **Delegação de eventos**: Captura o clique no botão por meio de delegação no elemento estático.
2. **Flexibilidade de seletores**: Permite o uso de IDs (`#id`) ou classes (`.class`) como seletor para o botão.
3. **Callback personalizável**: Executa uma função personalizada (`onClickCallback`) ao detectar o clique no botão.
4. **Inicialização automática**: O método `init` configura automaticamente o evento ao instanciar a classe.
5. **Método estático para facilidade de uso**: Método `init` facilita a criação de instâncias da classe.

Esses recursos tornam a classe adequada para lidar com cenários onde os eventos de clique precisam ser tratados de maneira dinâmica e eficiente, especialmente em interfaces que mudam ou carregam conteúdo dinamicamente.


## Sessão 00.01 - ✍️ 00.05.17.X - Preparando ambiente para criar gráficos de barra - Fase Final 👀

- **Primeiro Implementação**: 

    - [✍️ 00.05.17.X - Preparando ambiente para criar gráficos de barra - Fase Final 👀](https://github.com/H7-Dev/CONTROLER-FX/commit/d48082f23f8c37c302dc36e7a664bdba05d470a9)

        - [x] Implementado
        - [x] Serve como referência
        - [x] Revisado
        - [x] Debug e depuração (Necessário testar o envio do formulário no template)
        - [x] + Backup completo do banco de dados `(#01.01 db_controler_fx.sql)`

    - **Resumo**
        - Este gráfico de barras é altamente personalizável, com configurações detalhadas para responsividade, estilo de eixos, títulos, layout e cores. 
        - Ele inclui suporte para rótulos de dados diretamente nas barras e desativa tooltips em telas maiores para uma exibição mais limpa.
        - A função de redimensionamento ajusta dinamicamente as tooltips, garantindo que elas apareçam apenas em dispositivos menores
        - O gráfico é adaptável e ideal para diferentes tipos de visualizações, mantendo uma aparência consistente e profissional.

    - **Funcionalidades:**
        1. **Tipo do Gráfico**
            - **`type: 'bar'`**: Define o tipo de gráfico como um gráfico de barras. O Chart.js suporta vários tipos de gráficos, como `line`, `pie`, `doughnut`, `radar`, etc.

        2. **Configurações de Responsividade**
            - **`responsive: true`**: Torna o gráfico responsivo, ajustando-se automaticamente ao tamanho da tela do dispositivo.
            - **`maintainAspectRatio: true`**: Mantém a proporção original do gráfico ao redimensionar. Pode ser ajustado para `false` se for necessário permitir que o gráfico preencha seu contêiner de maneira não proporcional.

        3. **Configurações de Eixos**
            - **`scales`**: Configurações específicas dos eixos do gráfico.
            - **`y`**: Configurações para o eixo Y (vertical).
            - **`beginAtZero: true`**: Garante que o eixo Y comece do zero, o que é útil para evitar interpretações enganosas dos dados.
            - **`suggestedMax: valorMaximo + 1`**: Define um valor máximo sugerido para o eixo Y. Isso ajuda a ajustar automaticamente o gráfico para incluir uma margem acima do maior valor dos dados.
            - **`ticks`**: Configurações relacionadas às marcações (ticks) no eixo.
            - **`callback`**: Função para personalizar o formato das marcações. Neste caso, está configurado para mostrar apenas valores inteiros.
            - **`stepSize: 1`**: Define o intervalo entre as marcações no eixo Y, garantindo que cada marcação seja incrementada por 1.

        4. **Configurações de Título**
            - **`plugins.title`**: Configurações relacionadas ao título do gráfico.
            - **`display: true`**: Indica que o título deve ser exibido.
            - **`text: [...]`**: Define o texto do título, que pode ser uma string ou um array de strings para títulos em várias linhas.
            - **`color: '#333'`**: Define a cor do texto do título.
            - **`font.size: 16`**: Define o tamanho da fonte do título.
            - **`padding`**: Define o espaçamento ao redor do título.
            - **`top: 10`** e **`bottom: 10`**: Define 10 pixels de espaçamento acima e abaixo do título.

        5. **Configurações de Layout**
            - **`layout.padding`**: Define o espaçamento interno do gráfico (padding).
            - **`left: 10`, `right: 10`, `top: 10`, `bottom: 10`**: Adiciona 10 pixels de espaçamento em cada lado do gráfico, evitando que os elementos toquem as bordas do contêiner.

        6. **Configurações de Tooltip**
            - **`tooltip.enabled: false`**: Desativa as tooltips, que são pop-ups que aparecem ao passar o mouse sobre as barras do gráfico. Desativar as tooltips pode ser útil se você quiser um gráfico mais simples e limpo, ou se a interação não for necessária.

        7. **Configurações de Plugins**
            - **`plugins: [ChartDataLabels]`**: Ativa o plugin `ChartDataLabels`, que permite exibir rótulos de dados diretamente nas barras. Este plugin é útil para destacar os valores diretamente no gráfico.

        8. **Configurações de Cor**
            - **`backgroundColor`**: Define a cor de fundo dos elementos no gráfico.
              - **`'rgba(54, 162, 235, 0.2)'`**: Define a cor de fundo das barras na categoria "Recolhido".
              - **`'rgba(255, 99, 132, 0.2)'`**: Define a cor de fundo das barras na categoria "Retido".
            - **`borderColor`**: Define a cor da borda dos elementos no gráfico.
              - **`'rgba(54, 162, 235, 1)'`**: Cor da borda das barras "Recolhido".
              - **`'rgba(255, 99, 132, 1)'`**: Cor da borda das barras "Retido".
            - **`borderWidth: 1`**: Define a largura da borda das barras em pixels.

        9. **Espessura Máxima das Barras**
            - **`maxBarThickness: 50`**: Define a largura máxima das barras. Isso é útil para garantir que as barras não fiquem muito largas em gráficos com poucas categorias.

        10. **Mostrar Tooltip somente em telas menores**
            - **`updateTooltipOption`**: Essa função verifica o tamanho da tela e ajusta a configuração do `tooltip` do gráfico.
            - **Listener de Redimensionamento**: A função `updateTooltipOption` é chamada sempre que a janela é redimensionada, garantindo que o tooltip seja ativado ou desativado conforme necessário.
            - **Configuração Inicial**: A tooltip é inicialmente desativada, mas é atualizada logo após a criação do gráfico com base no tamanho da tela.

    >    Essa abordagem deve garantir que os tooltips sejam exibidos apenas em telas menores e sejam desativados em telas maiores, ajustando-se automaticamente se o usuário redimensionar a janela.
    Essas configurações são todas relacionadas ao estilo, apresentação e comportamento do gráfico em si, diferenciando-se das configurações e manipulação direta dos dados exibidos. Essas opções permitem personalizar a aparência e a funcionalidade do gráfico de acordo com as necessidades específicas da aplicação.



## Sessão 00.00 - ✍️ Domínio do Flexbox: Flex-basis, Flex-grow e Alinhamento Vertical 👀

- **Primeiro Implementação**: 

    - [00.05.02 ✍️ Domínio do Flexbox: Flex-basis, Flex-grow e Alinhamento Vertical 👀](https://github.com/H7-Dev/CONTROLER-FX/commit/b97f22f43f141ff0dc468d4f25f675870d3c9660)
    
    - **Resumo:**
        - Este commit aborda e corrige problemas relacionados ao layout vertical em um contêiner Flexbox, especificamente envolvendo o comportamento das propriedades `flex-basis`, `flex-grow`, e o alinhamento dos elementos dentro do contêiner.
        - O principal objetivo foi garantir que o elemento `div.main` ocupasse todo o espaço vertical restante de forma adequada e que os outros elementos fossem distribuídos e alinhados corretamente dentro do contêiner pai.

    - **Funcionalidades:**

        1. **Ajuste de `flex-basis` para melhorar o comportamento do layout**:
            - O valor de `flex-basis` foi redefinido para `auto` no elemento `div.main` para evitar que ele ocupasse toda a largura ou altura do contêiner prematuramente, permitindo um comportamento mais flexível e responsivo no layout.

        2. **Correção no uso de `flex-grow`**:
            - A propriedade `flex-grow: 1;` foi aplicada ao `div.main`, garantindo que ele ocupasse o espaço vertical restante de maneira consistente.

        3. **Implementação de `min-height: -webkit-fill-available;`**:
            - A altura mínima do contêiner pai (`div.pag-home`) foi ajustada para garantir que o layout preencha toda a altura disponível na viewport, proporcionando uma renderização adequada em navegadores WebKit.

        4. **Melhorias no alinhamento de elementos**:
            - Foram feitas melhorias no alinhamento dos elementos dentro do contêiner utilizando as propriedades `justify-content` e `align-items`, assegurando que os itens fossem distribuídos e alinhados conforme as expectativas do design.

        5. **Compatibilidade e responsividade melhoradas**:
            - As mudanças no layout aumentaram a compatibilidade com diferentes navegadores e dispositivos, assegurando que o design se adaptasse corretamente a diferentes tamanhos de tela.

        Essas funcionalidades garantem um layout flexível e responsivo, melhorando a experiência do usuário ao assegurar que os elementos sejam apresentados de maneira consistente e esteticamente agradável em diversas situações.


