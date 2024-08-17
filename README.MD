# ⚡ Flashcard Bars ALFA

_Descrição desse repositório_

Este repositório serve como uma documentação centralizada e de commits importantes de diversos projetos. Ele oferece links para buscas e acessos rápidos a commits relevantes. Duas coisas são fundamentais aqui. Primeiro, cada nova documentação deve ter o título começando com "Sessão" seguido pelo título do commit exatamente como está no projeto original. Segundo, para a "Primeira Implementação", o link deve direcionar para a primeira versão da classe ou código em questão.

## Sessão 00.00 - ✍️ Domínio do Flexbox: Flex-basis, Flex-grow e Alinhamento Vertical 👀

- **Primeiro Implementação**: 

    - [00.05.02 ✍️ Domínio do Flexbox: Flex-basis, Flex-grow e Alinhamento Vertical 👀](https://github.com/H7-Dev/CONTROLER-FX/commit/b97f22f43f141ff0dc468d4f25f675870d3c9660)
    
        Resumo:
        - Este commit aborda e corrige problemas relacionados ao layout vertical em um contêiner Flexbox, especificamente envolvendo o comportamento das propriedades `flex-basis`, `flex-grow`, e o alinhamento dos elementos dentro do contêiner.
        - O principal objetivo foi garantir que o elemento `div.main` ocupasse todo o espaço vertical restante de forma adequada e que os outros elementos fossem distribuídos e alinhados corretamente dentro do contêiner pai.

        Funcionalidades:

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


