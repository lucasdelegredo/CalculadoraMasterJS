# CalculadoraMasterJS

Calculadora para exercitar conhecimentos em Javascript, HTML e CSS

Criei esse projeto para exercitar e relembrar alguns conceitos de JAVASCRIPT, HTML e CSS.

Desse modo, utilizei design inspirado na calculadora de celular, desenvolvi a modelo do laoyut a ser seguido pelo PHOTOSHOP:
![PROJETOCALCULADORA](https://user-images.githubusercontent.com/74476423/125382138-80646100-e36b-11eb-8e69-5db38966fd33.png)

Desenvolvendo a ideia de como funcionaria a calculadora, pensei que seria interessante para exercitar alguns conceitos criar um VISOR secundário, o qual aparecesse a equação que ocasionou o resultado (mostrado no VISOR primário).

Começando a desenvolver, no HTML, foi criado um form com id="CALCULADORA",
nele foram criados toda a calculadora e seus botões.

Dois inputs são os VISORES
O restante são os botões da calculadora que possuem uma função onClick que passa como parâmetro o VALUE desse botão.

A função criada recebe o value dos botões e realiza a ação de mostrar o botão que foi clicado no VISOR, concatenando conforme os botões são pressionados:
![botaofunction](https://user-images.githubusercontent.com/74476423/125382669-7727c400-e36c-11eb-8e2c-826c4ba06964.PNG)

Posteriormente, foi criada uma função na qual seria correspondente ao botão C, que tem a função que limpar o que foi escrito no VISOR
![limparfunction](https://user-images.githubusercontent.com/74476423/125382751-a50d0880-e36c-11eb-8f40-e359947d262a.PNG)

Depois disso, era necessário que ele realizasse as contas, então foi criado uma função na qual seria executada quando o usuário pressionasse o botão IGUAL:
![igualfunction](https://user-images.githubusercontent.com/74476423/125382842-d1288980-e36c-11eb-9ba6-dd7f848494ce.PNG)
Foi criado também um radio button com um verificador condicional na calculadora caso o usuário desejasse visualizar o resultado arrendondado ou não.
Dessa forma, para que o resultado pudesse ser mostrado no VISOR 1, utilizou-se um comando do javascript chamado .eval()
![eval](https://user-images.githubusercontent.com/74476423/125383021-1cdb3300-e36d-11eb-9485-c054225b8cbf.PNG)
Esse comando faz a função de capturar o que está escrito no visor 1, e calcular em forma de uma expressão matemática. Então tudo o que foi digitado anteriormente é armazenado e mostrado no visor 2.

Desse forma funciona a calculadora, exercitando alguns conceitos de javascript com condicionais, funções, e conceitos de HTML e CSS integrados com JS.








