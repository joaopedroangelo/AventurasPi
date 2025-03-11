# Volume por Fatiamento

## Passo a Passo
1. Esboce o sólido e uma Seção Transversal que corte o sólido;
2. Encontre a fórmula da área da Seção Transversal;
3. Encontre os limites de integração;
4. Monte a integral.

---
### Macetes
#### 1. Fórmula Geral da Circunferência
A fórmula geral da circunferência é `X² + Y² = R²`. Sendo `R` o raio do sólido dado no enunciado, o `X` e o `Y` sendo os pontos no plano cartesiano.<br>
Use esta informação sempre que a seção transversal for uma circunferência e você não souber o raio dessa seção.<br>
Lembre que a área da circunferência é `πr²`, isole o Y da fórmula geral e terá uma fórmula para o raio da seção.<br>
Teremos: `Y = sqrt(R² - X²)`<br>

#### 2. Cone
Sempre que tiver um cone, a seção transversal será uma **círcunferência**. 

#### 3. Pirâmide de Base Quadrada ou Retangular
A seção transversal será sempre um **quadrado** (ou retângulo).

#### 4. Esfera, semi-esfera ou casca esférica
A seção transversal será uma **círcunferência**.

#### 5. Sólido de Revolução
Quando o sólido é obtido pela rotação de uma função em torno de um eixo, a seção transversal é sempre uma **círcunferência**. O raio dessa círcunferência é dado pelo valor da função que foi rotacionada.

---
### 1º Exemplo
> Encontre a integral que calcula o volume de uma pirámide de 3 metros de altura, com base quadrada de lado 3.<br>
> A pirâmide é cortada por uma seção transversal que é um quadrado de lado x.

Pelo enunciado, sabemos que a seção transversal é um quadrado de lado X. Logo, a fórmula da área dessa seção é X².<br>

Como a pirâmide tem 3 metros de altura, podemos desenhá-la no plano cartesiano do X = 0 até o X = 3.<br>
Sendo assim, os limites de integração são a = 0 e b = 3.<br>
![image](https://github.com/user-attachments/assets/1576ca4b-ef1c-4bdd-84f4-fe22b59f3f13)


Logo, a integral que resulta no volume desta pirâmide é:<br>
![image](https://github.com/user-attachments/assets/fc9bf1df-a2a3-4b40-8b18-c1b606257faa)

---
### 2º Exemplo
> O sólido está situado entre os planos perpendiculares X = 0 e X = 4.<br>
> As seções transversais que cortam este sólido são quadrado cujos lados se estendem de Y = -√x até Y = √x<br>
> Encontre a integral que resulta no volume deste sólido.

O esboço do sólido é o seguinte:<br>
![image](https://github.com/user-attachments/assets/6cb6fec7-771d-4476-bdc1-a344d7a13b2f)

As seções transversais são quadrados cujos lados são:<br>
![image](https://github.com/user-attachments/assets/da92d48d-896d-4cbd-bddd-b78f545e4762)

Logo, a integral que calcula o volume do sólido acima é:<br>
![image](https://github.com/user-attachments/assets/14ca772b-3ddd-4bf4-92d1-91ddfd45e5f5)

---
### 3º Exemplo
> O sólido está entre os planos X = -1 e X = 1.<br>
> As Seções Transversais que cortam este sólido têm diametros que vão de Y = X² até Y = 2 - X².

Esboce o sólido: <br>
![image](https://github.com/user-attachments/assets/383f54c1-2876-4262-9133-c8ad50bdc9b8)

**O que foi feito acima?**<br>
Foi desenhada a curva Y = X² e a curva Y = 2 - X².<br>
As curvas se intesectam nos pontos X = -1 e X = 1.<br>

Como a curva Y = 2 - X² é quem está no topo, o diâmetro da seção transversal é dado por:<br>
D = (2 - X²) - (X²) = 2 - 2X²<br>

Logo, o raio da seção transversal é 1 - X².<br>
Sendo assim, a área da seção transversal é dada por πR² = π(1 - x²)²<br>

Portanto, a fórmula que calcula o volume do sólido acima é:<br>
![image](https://github.com/user-attachments/assets/bdcd562f-7074-4165-a108-9338acb51e37)

---
### 4º Exemplo
> O sólido está situado no plano carteasiano entre X = -1 e X = 1.<br>
> As seções transversais são quadrados cujas bases se estendem do semi-círculo Y = -√(1 - x²) até Y = √(1 - x²).<br>

Esboço do sólido: <br>
![image](https://github.com/user-attachments/assets/cacf503b-1c13-4f3a-a639-6baf4332bc4a)

**O que foi feito acima?**<br>
Foi desenhado ambos os semi-círculos, formando uma circunferência situada entre X = -1 e X = 1.<br>
Em seguida, foi encontrado o lado do quadrado que corta a circunferência.<br>

Agora, sabendo que a área do quadrado é dada por **lado²**, temos que a área é:<br>
![image](https://github.com/user-attachments/assets/adb5640a-8a43-4710-bc81-43a698a7315a)

Sendo assim, a integral que calcula o volume do sólido deste exemplo é:<br>
![image](https://github.com/user-attachments/assets/51f39524-71c1-480c-b4a2-6e875e98f044)

---
### 5º Exemplo
> O sólido está situado no plano carteasiano entre X = -1 e X = 1.<br>
> As seções transversais são quadrados cujas diagonais se estendem do semi-círculo Y = Raiz de -(1 - x²) até Y = (1 - x²).<br>

Observe que é quase o mesmo problema do 4º exemplo.<br>
Porém, agora o problema nos diz que as **diagonais** dos quadrados que se estendem no plano, não os lados.<br>
Assim, precisamos saber que **Diagonal² = 2 * Lado²**.

Logo, o valor abaixo, que antes era o lado do quadrado, agora é a diagonal do mesmo.<br>
![image](https://github.com/user-attachments/assets/1aa0c181-7783-4f99-9dbd-16b9b4424f4b)

Sabendo disso, você terá condições de resolver o problema 5

---
