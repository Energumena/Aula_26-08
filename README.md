# Aula_26-08
---
# Código VSCode
### Usar código por meio do modo edição!!

programa {
  funcao inicio() {
   inteiro numero 
   escreva(" Informe um número: ")
   leia(numero)
   se(numero >= 5) {
    escreva("O número é maior ou igual a 5")
    } senao {
        escreva( "O número é menor que 5")
    }

  }
}
--------------------------------------------------
programa {
  funcao inicio() {
   inteiro numero 
   escreva(" Informe um número: ")
   leia(numero)
   se(numero % 2 == 0) {
    escreva("O número é Par")
    } senao {
        escreva( "O número é Impar")
    }

  }
}
---------------------------------------------------
programa {
  funcao inicio() {
   inteiro numero1, numero2 
   escreva(" Informe um número: ")
   leia(numero1)
   escreva(" Informe outro número: ")
   leia(numero2)
   se(numero1 > numero2) {
    escreva("O 1° número é maior")
} senao se (numero1 < numero2){
        escreva("O 2° número é maior)
    }  senao {
        escreva("Os números são iguais")
    }
  }
}
---------------------------------------------------
programa {
  funcao inicio() {
   inteiro nota1, nota2, nota3, media
   escreva(" Informe a 1° nota: ")
   leia(nota1)
   escreva(" Informe a  2° nota: ")
   leia(nota2)
   escreva(" Informe a 3° nota: ")
   leia(nota3)
   media = (nota1+nota2+nota3)/3

    se(media >= 70){
    escreva(" Aprovado ")
}   senao se(media >= 40){
    escreva(" Recuperação ")
}   senao{
    escreva(" Reprovado ")
    
  }
}
