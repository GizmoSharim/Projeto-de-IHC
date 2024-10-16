# Produto 8: LightHouse.
Segundo Heričko, Šumak e Brdnik (2021) várias ferramentas podem ser usadas para avaliar a performace de um sistema, mas uma que vem se destacando é o Google Lighthouse. Esse é um instrumento de codigo aberto que que oferece uma perspectiva sobre o desempenho, a acessibilidade e otimização do site desejado, bem como demonstra as possíveis soluções para melhora-las. O lighthouse também pode ser um importante meio para verificar a experiencia do usuário, por meio de métricas como o Lasgest Contenful Paint (LCP), o Interaction to Next Paint (INP), o Cumulative Layout Shift (CLS), o First Contenful Paint (FCP) e o Time to first Byte (TTFB). 

Todos impactando diretamente na perspectiva que o usuário tem ao acessar determinado site, dessa forma esse produto busca apresentar os resultados gerais indicados pelo lighthouse (como apresentado na imagem abaixo) e, após, trazer uma análise sobre cada métrica, assim como discorrer sobre a acessibilidade que o sistema aliexpress.com possui. 

![image](https://github.com/user-attachments/assets/a8dc4c44-b821-4dd9-a8cc-7455b163338e)

Fonte: https://pagespeed.web.dev/analysis/https-www-aliexpress-com-gcp-300000544-w5mAJSydGG/e1uzaoj3n3?form_factor=desktop&category=performance&category=accessibility&category=best-practices&category=seo&hl=pt&utm_source=lh-chrome-ext
## Largest Contenful Paint (LCP)
![image](https://github.com/user-attachments/assets/341d3ba3-d7d3-4799-922f-c1d759d2d1ea)

O Largest Contenful Paint segundo Walton e Pollard da web.dev (2019) demonstra o tempo de carregamento do maior conteudo visivel na janela de visualização no momento que o usuário entrou pela primeira vez na página. Um bom resultado é entre 0 e 2,5 segundos, quando é necessário melhorias fica entre 2,6 e 4 segundos, acima disso significa um mau resultado. Verificando que o sistema obteve 2,5 significa uma boa experiencia de usuário no sentido de visualizar um bloco importante de texto do site o mais rápido possível.

Esse resultado coloca o site em uma vantagem importante em relação aos concorrentes, pois, segundo a mesma fonte, a velocidade é um importante fator na experiência, impactando diretamente na retenção do usuário. Como é observado no estudo de Lee et. al. (2024) onde o investimento nesse tópico aumentou a receita em pouco mais de 50% e a taxa de conversão de clientes em até 33%.

## Interaction to Next Paint (INP)
![image](https://github.com/user-attachments/assets/0aae65d7-91fc-4765-9472-57ed102d6f56)

Para Wagner (2022) o Interaction to Next Paint é o responsável por medir a responsividade dos elementos do sistema quando o usuário interage, ou seja, o tempo de resposta que algum elemento tem ao se interagir com o mesmo. Sua classificação é de 0 a 200 possui uma boa resposta, acima de 200 até 500 é preciso fazer melhorias, já, superando esse valor, indica que o sistema possui um tempo de resposta ruim. O site avaliado apresentou o resultado de 112 ms como resposta, indicando que seus elementos possuem um feedback visual bom quando os usuários interagem com os mesmos. Portanto, as respostas às interações do usuário são atendidas em um tempo hábil, consequentemente, afetando positivamente a experiência do usuário.
## Cumulative Layout Shift (CLS)
![image](https://github.com/user-attachments/assets/54f88e1e-5d1a-4971-995d-daaafa0cdeb9)

De acordo com Maranho (2023), o Cumulative Layout Shift é uma métrica que avalia o desempenho de web design e usabilidade, além de medir a estabilidade visual de uma página na web, analisando a quantidade de mudanças inesperadas no layout do site enquanto ele carrega e enquanto é utilizado pelo usuário.

Ademais, segundo Walton e Mihajlija (2023), os sites devem possuir uma pontuação de 0,1 ou menos para ser considerada uma boa pontuação, enquanto uma pontuação entre 0,1 e 0,25 indica que o site precisa de melhorias e uma pontuação acima de 0,25 é considerada ruim. Ao observar que a pontuação do site avaliado foi de 0,29, infere-se que o usuário pode ter uma experiência instável e com algumas distrações ao utilizar o sistema, causando até mesmo frustação para ele, visto que ele pode clicar em ícones indesejados.

Com esse resultado, o site fica para trás em relação a outros sites na classificação de resultados de pesquisa no mecanismo de busca Google, já que o mesmo usa como fator fundamental para a classificação, a experiência do usuário. Ou seja, visto que o site avaliado possui um CLS alto, o site acaba por não ficar bem avaliado.

## First Contenful Paint (FCP)
![image](https://github.com/user-attachments/assets/cdb94fa4-4c1a-4381-9785-15668b825230)

Para Holcombe (2024), First Contenful Paint é uma métrica que mede o tempo necessário para que o primeiro elemento do sistema apareça na tela do usuário.
Nesse contexto, Walton (2023) diz que uma pontuação de FCP é de 1,8 segundos, e uma pontuação entre 1,8 segundo e 3 segundos sinaliza que o site precisa de melhorias e uma pontuação acima de 3 segundos é ruim.

Com isso, ao verificar que o sistema recebeu uma pontuação de 1,7 segundos, conclui-se que o sistema gera uma boa experiência para o usuário no quesito de exibir um simples item na tela do usuário, que serve como um aviso para ele de que o site está carregando, pois se o navegador apenas mostrar uma tela em branco, o usuário poderia ficar em duvida se o site estava funcionando normalmente, além de minimizar a lentidão e melhorar o engajamento.

## time to First Byte (TTFB)
![image](https://github.com/user-attachments/assets/584bd5e3-a377-4337-96f1-357859074817)

Segundo Silva (2023), o Time To First Byte é uma métrica de desempenho que mede o tempo que o servidor demora para disponibilizar o primeiro byte do site para o browser de internet após o usuário ter solicitado, sendo que esse tempo é em milissegundos.

Além disso, na visão de Pollard e Wagner (2024), a pontuação ideal para essa métrica é de 800ms ou menos, e com a pontuação entre 800ms e 1800ms o sistema necessita de melhorias, enquanto uma pontuação ruim é aquela que ultrapassa os 1800ms. Ou seja, visto que site apresentou uma pontuação de 1300ms, é indicado que ele passe por melhorias para que esse tempo seja corrigido e assim, deixa a experiência do usuário ainda mais positiva.

Portanto, o servidor do sistema é rápido, respondendo em uma velocidade muito alta após receber uma solicitação, o que garante uma experiência leve e agradável para o usuário, entretanto, como já dito, é recomendado que site passe por melhorias para que o tempo de resposta melhore, já que o ideal é de 800ms ou menos.

## Acessibilidade
![image](https://github.com/user-attachments/assets/2c79bbca-0d18-4fd9-8c05-72089132b747)

O Google Lighthouse classificou o sistema com uma pontuação de 76 em acessibilidade, identificando algumas áreas de melhoria: falta de atributos em elementos, botões de entrada sem texto compreensível, baixo contraste em textos, e ausência da especificação do idioma principal no HTML da página. Quanto ao primeiro ponto, muitos elementos não textuais no site não possuem textos alternativos, o que é crucial para acessibilidade. Segundo a WEBAIM (2021), o texto alternativo substitui conteúdos visuais e não textuais, permitindo que pessoas com deficiência visual ou cognitiva compreendam esses elementos adequadamente.

Assim como no caso dos elementos visuais, o problema dos botões sem texto compreensível ocorre quando imagens ou objetos interativos, como botões gráficos, não possuem descrições claras no código-fonte. Isso dificulta o funcionamento correto de leitores de tela, prejudicando a navegação de usuários com deficiência visual. Além disso, o baixo contraste entre o texto e o fundo é outro problema identificado no site. De acordo com as diretrizes da WCAG (Web Content Accessibility Guidelines), é fundamental que haja um contraste suficiente entre texto e fundo para que as informações sejam percebidas facilmente por pessoas com deficiência visual.

Por fim, a falta de especificação do idioma principal da página no código HTML pode levar a problemas de leitura com leitores de tela. Sem essa especificação, o leitor de tela pode utilizar o idioma padrão do sistema do usuário, causando erros caso o idioma da página seja diferente, comprometendo a experiência de navegação.



# Produto 9: UEQ Online.

## Dados Coletados.

- Participante 1:
  
|Obstrutiva | 0  0  1  0  0  0  0 | De Apoio|
|-----------|---------------------|---------|
|Complicado1| 0  1  0  0  0  0  0  | Fácil|
|Ineficiente|0  0  0  1  0  0  0  |Eficiente|
|Confuso| 1  0  0  0  0  0  0  | Claro|
|chato| 0  0  0  0  1  0  0  | excitante|
|Não é interessante|0  0  0  1  0  0  0  |interessante|
|Convencional| 0  0  0  1  0  0  0  | Inventivo|
|Habitual| 0  0  1  0  0  0  0| Ponta|

- Participante 2:

|Obstrutiva | 0  1  0  0  0  0  0 | De Apoio|
|-----------|---------------------|---------|
|Complicado1| 0  1  0  0  0  0  0  | Fácil|
|Ineficiente|1  0  0  0  0  0  0  |Eficiente|
|Confuso| 1  0  0  0  0  0  0  | Claro|
|chato| 1  0  0 0  0  0  0  | excitante|
|Não é interessante|0  0  1  0  0  0  0  |interessante|
|Convencional| 0  0  0  0  0  1  0  | Inventivo|
|Habitual| 0  0  0  1  0  0  0| Ponta|

- Participante 3:

|Obstrutiva | 0  0  0  0  1  0  0 | De Apoio|
|-----------|---------------------|---------|
|Complicado1| 0  1  0  0  0  0  0  | Fácil|
|Ineficiente|1  0  0  0  0  0  0  |Eficiente|
|Confuso| 0  0  0  1  0  0  0  | Claro|
|chato| 0  0  0  1  0  0  0  | excitante|
|Não é interessante|0  0  0  0  0  0  1  |interessante|
|Convencional| 0  1  0  0  0  0  0  | Inventivo|
|Habitual| 0  0  0  0  0  1  0| Ponta|

- Participante 4:

|Obstrutiva | 1  0  0  0  0  0  0 | De Apoio|
|-----------|---------------------|---------|
|Complicado1| 1  0  0  0  0  0  0  | Fácil|
|Ineficiente|1  0  0  0  0  0  0  |Eficiente|
|Confuso| 1  0  0  0  0  0  0  | Claro|
|chato| 0  0  0  0  0  0  1  | excitante|
|Não é interessante|0  0  0  0  0  0  1  |interessante|
|Convencional| 0  0  0  1  0  0  0  | Inventivo|
|Habitual| 0  0  0  0  0  1  0| Ponta|

## Resultados UEQ Online

| Item |Media| Variancia | Std. Dev | Nº | Negativo | Positivo | Escala |
|------|-----|-----------|----------|----|----------|----------|--------|
|1     |-1,3 |2,9       |1,7       |4   |Obstrutivo|Condutor  |Qualidade Pragmatica|
|2     |-2,3 |0,3       |0,5       |4   |Complicado|Facil     |Qualidade Pragmatica|
|3     |-2,3 |2,3       |1,5       |4   |Ineficiente|Eficiente|Qualidade Pragmatica|
|4     |-2,3 |2,3       |1,5       |4   |Confuso   |Evidente  |Qualidade Pragmatica|
|5     |0,3 |6,3       |2,5       |4   |Aborrecido|Excitante |Qualidade Pragmatica|
|6     |+1,3 |4,3       |2,1       |4   |Desinteressante|Interressante|Qualidade Pragmatica|
|7     |0,0 |2,7       |1,6       |4   |Convencional|Original|Qualidade Pragmatica|
|8     |0,5 |1,7       |1,3       |4   |Comum      |Vanguardista|Qualidade Pragmatica|

Para a ferramenta de análise de dados do UEQ valores de média obtidos entre -0,8 e +0,8 representam neutralidade entre as faixas de experiência do usuário. Resultados negativos são descritos como abaixo de -0,8, já os positivos são valores acima de 0,8, sendo o limite de cada um -3 e +3 respectivamente, apesar de que pontuar acima de 2 seja extremamente dificil, visto que esse resultado é gerado a partir de uma média e pontuar em uma escala perfeita é improvável.

Contudo, a partir da análise da tabela é possível verificar os pontos negativos da experiência do usuário ao visitar o site em questão. Assim, é considerado como obstrutivo, complicado, ineficiente e confuso, proporcionando uma percepção desagradável ao cliente ter contado com o site. Do mesmo modo, houve neutralidade com relação ao sentimento de aborrecimento/excitante, convencional/original e comum/vanguardista. Por fim, os usuários o classificaram como interessante, sendo a única caracteristica positiva da pesquisa.

|qualidade pragmática|-2,0 |
|--------------------|-----|
|Qualidade Hedonica  |+0,5 |
|Geral               |-0,75|

Na relação de nota da qualidade pragmática, percebe-se que os usuários encontraram dificuldades na usabilidade e no aprendizado de realizar as funções no sistema. Já em relação à qualidade hedônica, a pontuação de +0,5 indica que os sentimentos dos usuários ao utilizar o sistema foram neutros. Contudo, embora a avaliação da usabilidade esteja bem abaixo de um nível positivo, o resultado geral entre as duas métricas demonstra que o sistema conseguiu se manter próximo à neutralidade.

# Referencias
Heričko, T.; Šumak, B.; Brdnik, S.. (2021). Towards Representative Web Performance Measurements with Google Lighthouse. 39-42. DOI: 10.18690/978-961-286-516-0.9. 

Holcombe, J. 2024. First Contentful Paint Explicado: Como Melhorar o seu Tempo. Disponível em: <https://kinsta.com/pt/blog/first-contentful-paint/>. Acesso em 12 out 2024.

Lee, H. et. al.(2024). Rakuten. WEB.DEV. Disponível em: <https://web.dev/case-studies/rakuten>. Acesso em: 10/10/2024.

Maranho, L. 2023. Cumulative Layout Shift (CLS): Saiba como melhorar a métrica. Disponível em: <https://liveseo.com.br/seo/cumulative-layout-shift-cls/#:~:text=CLS%2C%20ou%20Cumulative%20Layout%20Shift,de%20uma%20p%C3%A1gina%20da%20web>.  Acesso em: 12 out 2024.

Pollard, B.; Wagner, J. 2024. Tempo até o primeiro byte (TTFB). Disponível em: <https://web.dev/articles/ttfb?hl=pt-br#what_is_ttfb>. Acesso em 12 out 2024.

Silva, V. 2023. Time To First Byte (TTFB) O que é e sua importância. Disponível em: <https://www.inetweb.com.br/post/_ttfb?srsltid=AfmBOorMhMFI0YkqvsPuKRZgZC3bYCo5YYeMp1jvTQ2QXaZsVUwlrCp8>. Acesso em 13 out 2024.

Wagner, J. (2022). Interaction to next paint (INP). WEB.DEV. Disponível em:  <fonte: https://web.dev/articles/inp>. Acesso em: 10/10/2024.

Walton, P. 2023. First Contentful Paint (FCP). Disponível em: <https://web.dev/articles/fcp?hl=pt-br>. Acesso em: 13 out 2024.

Walton, P.; Mihajlija, M. 2023. Cumulative Layout Shift (CLS). Disponível em: <https://web.dev/articles/cls?hl=pt-br#what-is-a-good-cls-score>. Acesso em: 12 out 2024.

Walton, P.; Polard, B. (2019). Largest Contentful Paint (LCP). WEB.DEV. Disponível em: fonte: <https://web.dev/articles/lcp>. Acesso em: 11/10/2024

WEBAIM. (2021). Texto Alternativo. WEBAIM. Disponivel em: <https://webaim.org/techniques/alttext/>. Acesso em: 11/10/2024.
