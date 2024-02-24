 # DESAFIO - Classificador de nível de Herói - javascript

 > Este repositório foi criado para resolver a atividade do Bootcamp Potência Tech iFood - Programação do Zero da DIO.  

## Deve ser utilizado

- Variáveis
- Operadores
- Laços de repetição
- Estruturas de decisões

##Objetivo:

Crie uma variável para armazenar o nome e a quantidade de experiência (XP) de um herói, depois utilize uma estrutura de decisão para apresentar alguma das mensagens abaixo:

Se XP for menor do que 1.000 = Ferro


Se XP for entre 1.001 e 2.000 = Bronze


Se XP for entre 2.001 e 5.000 = Prata


Se XP for entre 5.001 e 7.000 = Ouro


Se XP for entre 7.001 e 8.000 = Platina


Se XP for entre 8.001 e 9.000 = Ascendente


Se XP for entre 9.001 e 10.000= Imortal


Se XP for maior ou igual a 10.001 = Radiante


## Saída

Ao final deve se exibir uma mensagem:
"O Herói de nome **{nome}** está no nível de **{nivel}**"
 

  
## SOLUÇÃO
 > A seguir é apresentado o código desenvolvido para resolver este desafio. Nesse código é informado o nome e o nível de classificação do jogador.


![image](https://github.com/Ritavoli/Classificador-Nivel-Heroi/assets/142617833/2d0822d1-adea-431a-b6b9-5f0a5ea0e8ae)

const nomeHeroi = "Alien"; 


const xpHeroi = 8000; 


let nivel;


if (xpHeroi < 1000) {


    nivel = "Ferro";

    
} else if (xpHeroi >= 1001 && xpHeroi <= 2000) {


    nivel = "Bronze";

    
} else if (xpHeroi >= 2001 && xpHeroi <= 5000) {


    nivel = "Prata";
} else if (xpHeroi >= 5001 && xpHeroi <= 7000) {


    nivel = "Ouro";
} else if (xpHeroi >= 7001 && xpHeroi <= 8000) {


    nivel = "Platina";
} else if (xpHeroi >= 8001 && xpHeroi <= 9000) {


    nivel = "Ascendente";
} else if (xpHeroi >= 9001 && xpHeroi <= 10000) {


    nivel = "Imortal";
} else {


    nivel = "Radiante";
}
console.log(`O Herói  ${nomeHeroi} está no nível  ${nivel}`);

