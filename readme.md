# HTML
- HyperText Markup Language

- Hiper Texto?
- Marcação
  -tags
  -atributos
- Linguagem
  -maneira de escrever

# CSS
  
- Apresentação visual para o cliente
- Estilos para o HTML
- Cascading Style Sheets
  - Folha de Estil em Cascata

# Declaração
- Seletor
- Propriedade e Valor

# Conceitos
- Cascata
- Especificidade
- Box Model
- Display block vs inline



### Imagem bola de cristal
https://gist.githubusercontent.com/maykbrito/0acdf4ce919838ffed50915a31fc5b23/raw/6f4dd01ec3116428ec4c99255944cb9ac7927590/cristal-ball.svg


// 1. Variáveis
  let estaChovendo = true
  const meuNome = "Axel"


// 2. Tipos de Dados
  // String
  // ""
  // ''

  // Number
  // 12 - Integer (+ -)
  // 3.2 - Float (+ - )

  // Boolean
  // true ou false
  // const maiorDeDezoito = false

  // undefined - indefinido

   
// 3. Operadores
  // Atribuição (ex: =2)
    // atribui valor
  let n1 = 12
  let n2 = 3

  // Aritméticos (ex: * / + -)
  // calculos matemáticos simples

  // Concatenação de String (+)

  // Comparação (ex: < > == )
  // transforma a expressão em true ou false
  // const maiorQue = 1 > 2 // false
  // const IgualA = 1 == 1 // true

// 4. Condicional (if/else)
  // const idade = 17
  // const maiorDeDezoito = idade >= 18

  if(maiorDeDezoito) {
    alert("Pode tirar carteira de motorista")
  } else {
    alert("Não pode tirar")
  }

// 5. Estrutura de Dados
  // Array- Vetor - Lista
  // Array -----          0     1   2  3
  const temperaturas = [23.3, 32.2, 1, 5] 


 // Object
 // const pessoa = {
   nome: "Axel",
   idade: 38,
   filhos: ["K", "E", "J", "L", "G"]
 }


// 6. Function
  // 1. Criação
  // function nomeDaFuncao () {
    console.log('código dentro da função')
  }

  // 2. Execução
  // Parâmetros
  // function soma(a, b) {
    console.log(a + b)
  }
  soma(34, 45)
  soma(90, 54)

  // Retorno
  function soma(a, b) {
    return a + b
  }

  // const multiplica = soma(2, 2) * 4
  // console.log  (multiplica)

  console.log(soma(2,2))


// 7. Extensões da Linguagem (ex.: Math, Date ...)

  // Math.random()
  // Math.floor(1.2)
  // Math.ceil(1.2)
  // Math.Propriedade

// 8. DOM - Document Object Model

  // window
  // window.alert("alerta")
  // document
  // documento.writer("texto")
  // manipular elementos
  // documento.documentElement.style.background = "white"