#PF
# Lista 2
##### Q2. Programa para calcular a área de uma circunferência dado o valor do raio.
```js
const pi = 3.14;
const raio = 2;

function areaCirc() { 
	return 2 * pi * raio; 
}
```
##### Q3. Programa para determinar se três valores passados podem representar um triângulo ou não.
```js
const v1 = 2, v2 = 3, v3 = 5;

function trianguloCheck(a, b, c) { 
	if(a <= 0 || b <= 0 || c <= 0) return "Não é um triangulo";
 	else return "É um triangulo";
}
```
#####  Q4. Programa para classificar um triângulo em Equilátero, Isósceles ou Escaleno a partir dos valores de seus três lados.
```js
const v1 = 2, v2 = 3, v3 = 4;

function trianguloCheck(a, b, c) { 
	if(a <= 0 || b <= 0 || c <= 0) return "Não é um triangulo";
  
  if(a == b && b == c) return "Equilatero";
  else if(a == b && b != c || b == c && a != c || a == c && a != b) return "Isósceles";
  else return "Escaleno";
  
}

console.log(trianguloCheck(v1, v2, v3))
```

#####  Q5. Programa para calcular a distância euclidiana entre dois pontos $[(x_1, y_1), (x_2, y_2)]$ no plano cartesiano. Utilize a equação geral da reta para calcular a distância quando a reta não for paralela a nenhum dos eixos (abscissas ou ordenadas) e as versões simplificadas quando for paralela.
```js
function distancia(x1, y1, x2, y2) { 
	if(x1 == x2) return Math.abs(y1 - y2)
  else if (y1 == y2) return Math.abs(x1 - x2);
  else return Math.sqrt((x1 - x2)**2 + (y1 - y2)**2);
}

console.log(distancia(2, 2, 3, 3))
```

##### Q6. Fornecidos três valores, a, b e c, escreva um programa que retorne quantos dos três são iguais. A resposta pode ser 3 (todos iguais), 2 (apenas um diferente) ou 0 (todos diferentes).
```js
function quantosIguais(a, b, c) { 
	if(a == b && b == c) return 3;
	else if(a == b || b == c || a == c) return 2;
	else return 0;
}

console.log(quantosIguais(3, 3, 3))
```

##### Q7. Programa para retornar o menor valor entre três números quaisquer. Tente resolver considerando o subproblema de determinar o menor valor entre dois números quaisquer (obs.: em caso de valores iguais, deve-se retornar como resultado o próprio valor).
```js
function menorValor(a, b, c) { 
	if(a < b)
  {
  	if(a >= c) return c;
    else return a;
  }
  else if (b < c) return b;
  else return c;
}

console.log(menorValor(6, 7, 5))
```
##### Q8. Escrever um programa que calcule o valor de um número elevado à quarta potência. Tente fazer uso do subproblema de calcular o quadrado de um número qualquer.
```js
function nPotencia(b, e) { 
	return b**e
}

console.log(nPotencia(2, 4));
```
##### Q9. Programa que calcula o "ou-exclusivo" entre dois valores-verdade (verdadeiro ou falso), dado por a⊗b=(a∨b)∧¬(a∧b)
```js
function ouexclusivo(a, b) { 
	if((a && !b) || (b && !a)) return true;
  else return false;  
}

console.log(ouexclusivo(false, false));
```

##### Q10. Escreva um programa que dados o primeiro nome e o último sobrenome de uma pessoa qualquer, retorne-os em forma de citação bibliográfica conforme exemplo: Fulano Santos --> Santos, Fulano.
```js
function citacaoBib(nome, sobrenome)
{
	return `${sobrenome}, ${nome}`;
}

console.log(citacaoBib("Thiago", "Vasconcelos"));
```

##### Q11. Dados três valores, escreva um programa que retorne quantos desses três valores são maiores que o valor médio entre eles.
```js
function maiorQueMedia(x, y, z)
{
	const m = (x+y+z)/3;

	if(x > m) //X Y, X Z, X
  {
  	if(y > m) return 2;
    else if(z > m) return 2;
    else return 1;
  }
  
  else if(y > m){ // Y Z, Y
  	if(z > m) return 2;
    else return 1;
  }
  
  else if(z > m) return 1; // Z
  else return 0;
}

function maiorQueMedia2(x,y,z)
{
	const m = (x+y+z)/3;
  let num = 0;
  if(x>m) num++;
  if(y>m) num++;
  if(z>m) num++;
  
  return num;
}

const a = 1, b = 1, c = 7;

console.log(`Numeros: ${a}, ${b}, ${c} | ${maiorQueMedia(a,b,c)}`);
console.log(`Numeros: ${a}, ${b}, ${c} | ${maiorQueMedia2(a,b,c)} (segunda fun.)`);
```
##### Q12. Escreva um programa para calcular o maior e o menor valor real das raízes de uma equação de segundo grau. A expressão genérica para cálculo das raízes é dada por $\dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a}$
```js
function raizes(a, b, c)
{
	const raiz1 = (-b + Math.sqrt(b**2 - 4 * a * c))/(2 * a);
	const raiz2 = (-b - Math.sqrt(b**2 - 4 * a * c))/(2 * a);
  
	return raiz1 > raiz2 ? 
		`Raizes ${raiz1} e ${raiz2}, ${raiz1} sendo maior` 
	  	: `Raizes ${raiz2} e ${raiz1}, ${raiz2} sendo maior`
}

console.log(raizes(1, -6, 5));
```
##### Q13. Um móvel com velocidade constante percorre uma trajetória retilínea. Considere $t_0 = 0$, o instante inicial e $x_0 = 500$ a posição inicial. Escreva um programa para calcular a velocidade do objeto em um dado instante _t_ e posição _x_.
```js
function velocidade(pos, tempo)
{
	const t0 = 0, x0 = 500;
  const dx = pos - x0;
  
  return dx/tempo;
}

console.log(velocidade(660, 2));
```
##### Q14. Programa que escreva por extenso um determinado algarismo passado como argumento.
```js
const extenso = (a) => {
    switch(a){
        case 0: return "zero";
        case 1: return "um";
        case 2: return "dois";
        case 3: return "tres";
        case 4: return "quatro";
        case 5: return "cinco";
        case 6: return "seis";
        case 7: return "sete";
        case 8: return "oito";
        case 9: return "nove";
        default: return "Algarismo invalido"
    }
 }
```
```js
function extenso(num)
{
	const reversedString = num.split('').reverse().join('');
	const splits = reversedString.match(/.{1,3}/g);
  const result = splits.map(function(substring) {
    return substring.split('').reverse().join('');
  }).reverse();
	const casas = result;
  
  const sufixos = [ 'Decilhões', 'Nonilhões', 'Octilhões', 'Septilhões', 'Sextilhões', 'Quintilhões', 'Quadrilhões', 'Trilhões', 'Bilhões', 'Milhões', 'Mil', '' ];
	
  
  const casasExtenso = casas.map((valor, index) => `${valor.length >= 2 ? centenasExtenso(valor[0]) + ' e '  : ''} ${valor.length >= 2 ? dezenasEUnidadesExtenso(valor.substring(1)) : dezenasEUnidadesExtenso(valor) } ${sufixos[index + (sufixos.length - casas.length)]}`)
  return casasExtenso.join(" , ");
}


function centenasExtenso(num)
{
	const centenas = [ '', 'Cento', 'Duzentos', 'Trezentos', 'Quatrocentos', 'Quinhentos', 'Seiscentos', 'Setecentos', 'Oitocentos', 'Novecentos' ];
	return centenas[parseInt(num)];
}
function dezenasEUnidadesExtenso(n)
{	
	const num = n.length > 2 ? n.substring(n.length - 2) : n;
	const dezenas = [ '', 'Dez', 'Vinte', 'Trinta', 'Quarenta', 'Cinquenta', 'Sessenta', 'Setenta', 'Oitenta', 'Noventa' ];
  const numeros11a19 = [ 'Onze', 'Doze', 'Treze', 'Catorze', 'Quinze', 'Dezesseis', 'Dezessete', 'Dezoito', 'Dezenove' ];
  const unidades = [ '', 'Um', 'Dois', 'Três', 'Quatro', 'Cinco', 'Seis', 'Sete', 'Oito', 'Nove' ];
	const valor = parseInt(num);

  
  if(valor >= 11 && valor <= 19) return numeros11a19[parseInt(num[1]) - 1]
  else if (valor < 10) return unidades[valor];
  else if (valor == 0) return 'Zero';
  else return `${dezenas[parseInt(num[0])]} e ${unidades[parseInt(num[1])]}`
}
const numero = '1280598217423268739'
console.log(`${numero} por extenso é: ${extenso(numero)}`)
```