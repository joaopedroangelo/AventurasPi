# Método do Anel - Cálculo do Volume de Sólidos de Rev.

---
## Quando usar?

### Método do Anel
Geralmente usa duas curvas: O método do anel é usado quando duas curvas definem a região a ser girada em torno de um eixo.

**Características:**
1. Há uma curva interna e uma curva externa em relação ao eixo de rotação.
2. A região entre as duas curvas cria um anel quando girada, resultando em um sólido com um "furo" ou espaço vazio no centro.
3. O volume é calculado subtraindo o volume formado pela curva interna do volume formado pela curva externa.

**Método do Disco:** Uma curva delimitando a região (volume sólido sem buraco).<br>
**Método do Anel:** Duas curvas delimitando a região (volume com um buraco no centro).

---
## Passo a Passo

1. Identificar as funções que serão rotacionadas;
2. Identificar qual o eixo de rotação;
3. Verificar qual função será o raio externo (é a que está mais distante do eixo de rotação);
4. Verificar qual função será o raio interno (é a que está mais próxima do eixo de rotação);
5. Montar a fórmula do volume (V = π(R² - r²)), sendo **R** o raio externo e **r** o raio interno; 
6. Montar a integral;

---
## Exemplo 1

> A região delimitada pela curva g(x) = X² + 1 e pela reta f(x) = -X + 3 gira em torno do eixo X, gerando um sólido.<br>
> Determine a integral que calcula o volume deste sólido.

Primeiro, vamos montar o gráfico:<br>
![image](https://github.com/user-attachments/assets/199ef9a1-9dd2-4e26-9550-8a5e25fbd7da)

**Agora, identifique os limites de integração:** <br>
Basta fazer g(x) = f(x)<br>
X² + 1 = -X + 3<br>
Iremos encontrar X = -2 e X = 1

**Agora, identifique o raio externo e o raio interno:** <br>
O raio externo é a função que está mais distante do eixo de rotação, que nesta questão é o X.<br>
Como podemos ver no gráfico, o raio externo é **-X + 3**;<br>
O raio interno é **X² + 1**;<br>

Assim, a integral que calcula o volume do sólido é:<br>
![image](https://github.com/user-attachments/assets/cd9f8487-3ab3-42a2-b0d6-1b9f0c508ecc)

---
## Exemplo 2

> A região compreendida entre a parábola f(x) = X² e g(x) = 2X no 1º quadrante gira em torno do eixo Y.<br>
> Determine o volume do sólido.

Montando o gráfico:<br>
![image](https://github.com/user-attachments/assets/d5d64672-bee4-498e-8148-252ff8f67ce1)

Encontrar qual o raio externo e o interno:<br> 
> Observe que, dessa vez, a rotação é em torno do eixo Y, logo as funções devem estar em função do Y.<br>
> Na imagem abaixo, é isso que está sendo feito. Pega a função que foi dada e isola o Y.<br>

![image](https://github.com/user-attachments/assets/74a7a571-f0a6-44e5-98e4-1913d36114ef)
![image](https://github.com/user-attachments/assets/809f826d-d870-4d43-a479-5d19638224fc)

Limites de Integração:<br>
![image](https://github.com/user-attachments/assets/d772ef8f-c887-4cea-988c-2a40c7407c2f)

Montagem da Integral:<br>
![image](https://github.com/user-attachments/assets/cdea52ff-04fb-40dc-8ae0-80a74ddff76e)
