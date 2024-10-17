# Relatório de Inspeção de Usabilidade

## Objetivo:<br/>
O principal objetivo deste relatório é identificar problemas de usabilidade na interface do sistema em análise, avaliando sua aderência a heurísticas de design e interação, com foco em possíveis melhorias para a experiência do usuário.

## Método utilizado:<br/>
Os métodos de Inspeção estão relacionados aos aspectos da usabilidade do sistema, ou seja, eles ajudam a identificar os problemas, ajuda a resolvê-los com recomendações ou eliminações dos mesmos. Vale ressaltar que, os problemas de usabilidade dificultam na efiência, aprendizagem e na satisifação do usuário em relação ao uso do software.<br/>

A inspeção de usabilidade foi realizada utilizando a técnica de Avaliação Heurística, na qual especialistas analisam a interface de acordo com um conjunto de princípios conhecidos como heurísticas de usabilidade. Foram utilizados os princípios de Nielsen como base para a identificação dos problemas.<br/>

Estas princíppios ou heurísticas, são basicamente os "dez mandamentos" da IHC (Interação Humano-Computador), caso violadas, significa que o sistema não está bom e que precisa de melhorias.

## Conjunto de heurística<br/>
**Foram utilizadas as 10 heurísticas de Nielsen:**<br/>
1. Visibilidade do status do sistema.<br/>
2. Compatibilidade entre o sistema e o mundo real.<br/>
3. Controle e liberdade do usuário.<br/>
4. Consistência e padrões.<br/>
5. Prevenção de erros.<br/>
6. Reconhecer em vez de lembrar.<br/>
7. Flexibilidade e eficiência de uso.<br/>
8. Estética e design minimalista.<br/>
9. Ajudar os usuários a reconhecer, diagnosticar e corrigir os erros.<br/>
10. Ajuda e documentação.<br/>

## Quantidade e perfil dos avaliadores<br/>
A avaliação contou com seis avaliadores (A1, A2, A3, A4, A5 e A6), todos em fase de especialização em usabilidade e interação humano-computador, com experiência (que foi adquirida recentemente) em avaliação de interfaces e análise de sistemas digitais.<br/>

### Tabela em relação aos avaliadores:
| Avaliador |             Nome              |         Perfil        | Experiência Técnica | Conhecimento do Sistema |
|-----------|-------------------------------|-----------------------|---------------------|-------------------------|
|    A1     |Adam Andrade Ribeiro           |    Usuário avançado   |    Básica           |        Intermediário    |
|    A2     |Aila Karoline Santana Moreira  | Usuária avançada      |    Avançada         |         Moderado        |
|    A3     |Geovanni Ferreira Marques Veras|                       |                     |                         |
|    A4     |Gustavo de Oliveira Pena       |                       |                     |                         |
|    A5     |Ícaro de Abreu Silva           |                       |                     |                         |
|    A6     |Sabrina Martins Bezerra        | Usuária intermediária |  Intermediária      |         Moderado        |

## Processo da Inspeção de Usabilidade<br/>
Cada avaliador foi incumbido de navegar e avaliar diferentes partes da interface, identificando problemas de usabilidade de acordo com as heurísticas. Para isso, foi utilizada uma extensão no Google Chrome, conhecida como "UX Check", na qual foi possível classificar o nível de severidade, a heurística violada, escrever a descrição do problema encontrado e, por fim, proporcionar uma melhoria ou recomendação para o problema encontrado. As recomendações também foram documentadas para ajudar na correção dos problemas identificados.<br/>

## Problemas de usabilidade encontrados<br/>
Consolidação dos problemas de usabilidade.

| Avaliadores  | Heurística                           | Discrepâncias repetidas | Classificação   | Justificativa                                           | Solução                                      |
|--------------|--------------------------------------|-------------------------|-----------------|-------------------------------------------------------|----------------------------------------------|
| A1, A2       | Prevenção de Erros                   | Sim                     | Defeito real    | Menus de categorias "Choice" e "Plus" pouco intuitivos. |Mudar a lista de categorias para tornar mais claro para novos usuários. |
| A1, A2       | Prevenção de Erros                   | Sim                     | Defeito real    | Produto abre em nova aba desnecessariamente.           | Abrir o produto diretamente na página sem nova aba. |
| A1           | Visibilidade do Status do Sistema    | Não                     | Falso-positivo  | Cor pode sugerir ação pendente ao usuário.              |Usar cores mais transparentes nos ícones. |
| A1           | Reconhecer ao invés de Relembrar     | Não                     | Falso-positivo  | Uso de hyperlink ao invés de ícones para funções.       |Substituir hyperlinks por ícones intuitivos. |
| A1           | Compatibilidade com o Mundo Real     | Não                     | Defeito real    | Uso de palavra desconhecida para usuários.              |Usar uma expressão mais conhecida para evitar confusão. |
| A1           | Prevenção de Erros                   | Não                     | Defeito real    | Produtos com diferentes preços na mesma aba.            |Dividir produtos por modelo e preço para evitar engano. |
| A1, A2       | Compatibilidade com o Mundo Real     | Sim                     | Defeito real    | Mistura de idiomas na plataforma.                      | Usar apenas um idioma, preferencialmente português. |
| A2           | Compatibilidade com o Mundo Real     | Não                     | Falso-positivo  | Informações estão desorganizadas em outro idioma.       | Organizar informações e garantir que estejam no idioma correto. |
| A2           | Estética e Design Minimalista        | Não                     | Falso-positivo  | Parte do banner não é visível.                         | Ajustar o tamanho e posição do banner para melhor visibilidade. |
| A2           | Visibilidade do Status do Sistema    | Não                     | Defeito real    | Botão não funciona e não informa motivo.               | Implementar mensagens de erro claras quando o botão falhar. |
| A2           | Prevenção de Erros                   | Não                     | Defeito real    | Senhas fracas são permitidas.                          | Implementar regras mais rígidas para criação de senhas. |
| A2           | Visibilidade do Status do Sistema    | Não                     | Defeito real    | Botão "acessibilidade" apenas recarrega a página.       | Corrigir funcionamento do botão de acessibilidade. |
| A2           | Ajuda e Documentação                 | Não                     | Defeito real    | Função "Choice" não é explicada no site.               | Adicionar uma explicação detalhada sobre a função "Choice" na central de ajuda. |
| A3           | Consistência e Padrões               | Não                     | Falso-positivo  | Usuário precisa aprender novos ícones e navegação.      | Adotar ícones mais intuitivos e padrões conhecidos para facilitar a navegação. |
| A2, A3       | Ajuda e Documentação                 | Sim                     | Defeito real    | Documentação insuficiente para suporte ao usuário.     | Criar uma documentação de ajuda acessível e fácil de entender para os usuários. |
| A2, A3       | Compatibilidade com o Mundo Real     | Sim                     | Defeito real    | A busca não retorna resultados adequados ao contexto.  | Melhorar o algoritmo de busca para que retorne resultados relevantes. |
| A4           | Design Estético e Minimalista        | Não                     | Defeito real    | Falta de ícones dificulta a identificação de links.    | Adicionar ícones diferenciados para indicar links claramente. |
| A4           | Design Estético e Minimalista        | Não                     | Defeito real    | Produtos são exibidos sem categorização adequada.      | Classificar os produtos adequadamente por tipo. |
| A1, A4       | Design Estético e Minimalista        | Sim                     | Falso-positivo  | Excesso de informações induz o usuário ao erro.        | **Recomendação A1**: Minimizar as informações exibidas para novos usuários. |
| A4           | Consistência e Padrões               | Não                     | Falso-positivo  | Ícone de loja não transmite seu significado.            | Tornar o ícone de loja mais claro e explicativo sobre sua função. |
| A5           | Prevenção de Erros                   | Não                     | Falso-positivo  | Usuário pode ser levado a pensar que o frete é grátis.  | Destacar claramente as condições de frete para evitar confusão. |
| A5           | Design Estético e Minimalista        | Não                     | Falso-positivo  | Excesso de informações em um só lugar.                 | Distribuir as informações de forma mais organizada e clara. |
| A6           | Reconhecer ao invés de Relembrar     | Não                     | Defeito real    | Abas não deixam claro para onde o usuário será direcionado. | Adicionar descrições ou ícones que indiquem para onde cada aba redireciona. |
| A6           | Reconhecer ao invés de Relembrar     | Não                     | Defeito real    | Ícone "fantasia" não é claro quanto à sua função.      | Melhorar o design do ícone "fantasia" para torná-lo mais intuitivo. |
| A6           | Visibilidade do Status do Sistema    | Não                     | Defeito real    | Informações de telas anteriores sobrepõem-se às novas. | Corrigir o bug que faz com que informações antigas permaneçam visíveis. |
| A2, A6       | Consistência e Padrões               | Sim                     | Defeito real    | Ícone de "preços" redireciona para abas irrelevantes.  | Corrigir o redirecionamento do ícone para abas corretas. |

