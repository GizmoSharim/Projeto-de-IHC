# Tabela de Coleção de Defeitos

Descrição: Processo de eliminação de discrepâncias repetidas, resultando em uma lista composta apenas por discrepâncias únicas.
| ID | Inspetores |                      Descrição do problema                                                          |     Heurísticas Violadas      | Severidade |
|----|------------|-----------------------------------------------------------------------------------------------------|-------------------------------|------------|
|  1 |      A1    |  Menus de categoria pouco intuitivos referente ao que é "Choice" e "Plus".                          |        Prevenção de Erros     |      2     |
|  2 |      A1    |  Induz ao usuário abrir uma nova aba ao invés de mostrar o produto imediatamente.                   |       Prevenção de Erros      |      2     |    
|  3 |      A1    |  A cor pode indicar ao usuário algo pendente nessas categorias.                                     |       Visibilidade do Status do Sistema|            |     
|  4 |      A1    |  Uso de hyperlink para as funções, recomendação de usar ícones        	                         |Reconhecer ao invés de Relembrar |            |    
|  5 |      A1    |  Palavra desconhecida, recomendação de usar uma expressão conhecida.                                |Compatibilidade com o Mundo Real                        |            |     
|  6 |      A1    |  Produtos com preços diferentes na mesma aba, recomendação de dividir por modelo e preço.           |Prevenção de Erros                        |            |
|  7 |      A1    |  Mistura de idiomas, recomendação de usar apenas um idioma.                                         |Compatibilidade com o Mundo Real                        |            |
|  8 |      A2    |  Informações desorganizadas e em outro idioma, ao clicar no botão de Big Save.                      |Compatibilidade com o Mundo Real                        |            |     
|  9 |      A2    |  Informações do banner não estão totalmente visíveis.                                               |Estética e Design Minimalista                        |            | 
| 10 |      A2    |  Botão de "Adicionar ao carrinho" não funciona e não explica o motivo.                              |Visibilidade do Status do Sistema                        |            |
| 11 |      A2    |  As regras para a senha não são aplicadas corretamente, permitindo uma senha sem números e símbolos.|Prevenção de Erros                        |            |
| 12 |      A2    |  Botão "acessibilidade" não funciona, apenas recarrega a página.                                    |Visibilidade do Status do Sistema                       |            |
| 13 |      A2    |  A função "Choice" aparece em todo o site, mas não é explicada, nem na central de ajuda.            |Ajuda e Documentação                               |            |
| 14 |      A3    |  O usuário precisa aprender novos métodos ao usar o sistema, explorando ícones e telas.             |Consistência e Padrões                               |            |
| 15 |      A3    |  O sistema não oferece documentação ou ajuda acessível para os usuários resolverem problemas.       |Ajuda e Documentação                              |            |
| 16 |      A3    |  A busca do sistema não retorna resultados adequados ao contexto.                                   |Consistência e Padrões                             |            |
| 17 |      A4    |  Informações espalhadas e sem ícones ou cores diferentes para indicar que são links.                |Compatibilidade com o Mundo Real                               |            |
| 18 |      A4    |  O sistema exibe muitos produtos sem classificação do tipo de produto.                              |Design Estético e Minimalista                               |            |
| 19 |      A4    |  Muito texto e informações para especificar o produto e a compra, induzindo o usuário ao erro.      |Design Estético e Minimalista                               |            |
| 20 |      A4    |  O ícone que parece uma lojinha não descreve seu significado, induzindo o usuário ao erro.          |Design Estético e Minimalistas                               |            |
| 21 |      A5    |  O usuário pode ser levado a acreditar que o frete do produto é grátis por observação rápida.       |Consistência e Padrõe                   |            |     
| 22 |      A5    |  Muita informação em um só espaço.                                                                  |Prevenção de Erros                                          |            |
| 23 |      A6    |  Abas pressionadas não explicam para onde o usuário será direcionado.                               | Design Estético e Minimalista                               |            |
| 24 |      A6    |  Ao clicar nos três pontinhos, são exibidas imagens confusas, como o ícone "fantasia", que não transmite sua função claramente. |  Reconhecer ao invés de Relembrar                             |            |
| 25 |      A6    |  O site apresenta um bug com informações anteriores sobrepondo-se às posteriores.                   |                               |            |
| 26 |      A6    |  Ícone de "preços" não segue o padrão da pesquisa, redirecionando para abas irrelevantes.           |Reconhecer ao invés de Relembrar                              |            |


| ID | Inspetores | Descrição do problema |          Heurísticas Violadas                    | Severidade |
|----|----------------|-----------------------|--------------------------------------------------|------------|
|  1 | A1, A2, A3, A4 |            Muita informação exibida na tela inicial, o que pode confundir o usuário.           |       Design Estético e Minimalista              |      2      |
|  2 |       A1, A2, A3, A4, A6     |           Texto, ícones e fontes inconsistentes, causando confusão e falta de uniformidade visual.            |       Consistência e Padrões                     |      3      |    
|  3 |      A1, A2, A3      |            A pesquisa ou navegação do sistema resulta em erros ou confusões para o usuário, induzindo-o a tomar decisões incorretas.           |       Prevenção de Erros                         |     3       |       
|  4 |      A1, A2, A6      |          	Informações dos produtos e status do sistema não estão totalmente visíveis ou claras.             |       Visibilidade do Status do Sistema          |     2       |    
|  5 |      A1, A2, A6      |         O sistema utiliza ícones sem explicar suas funções, exigindo que o usuário memorize ou deduza suas funcionalidades.              |       Reconhecer ao invés de Relembrar           |      3      |      
|  6 |         	A1, A2, A3, A4   |         O sistema apresenta opções, termos ou informações que não fazem sentido no contexto do mundo real.              |       Compatibilidade do Sistema com o Mundo Real|     3       |      
|  7 |        A2, A4    |         	O sistema não oferece uma maneira fácil de o usuário retornar à página anterior, limitando sua liberdade de navegação.              |       Controle e Liberdade do Usuário            |      3      |      
|  8 |      A2      |              A pesquisa retorna resultados irrelevantes, o que frustra o usuário ao não encontrar o que procura.         |       Flexibilidade e Eficiência de Uso          |      4      |      
|  9 |        A2, A3    |            O sistema não oferece documentação ou ajuda acessível, levando o usuário a frustração por não conseguir suporte quando necessário.           |      Ajuda e Documentação                        |      2      |      

     

