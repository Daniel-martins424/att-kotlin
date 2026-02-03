# Exercicio 1:

    fun main() {

    var entrada_celsius = 30  
    
    //F = c * 9/5 + 32 
    
    var F = entrada_celsius * 9/5 + 32
    
  print (F)
}

_____________________________________________________________________________________________________________________________

# Exercicio 2:

    fun main() {
    
    var entrada_fahrenheit = 77  
    
    var F = (entrada_fahrenheit * - 32) * 5/9
    
  print (F)
}

____________________________________________________________________________________________________________________________

# Exercicio 3:


fun main() {

    var raio = 5
    var altura = 10

    // V = π * raio² * altura

    var volume = Math.PI * raio * raio * altura

  print(volume)
}
____________________________________________________________________________________________________________________________

# Exercicio 4:
    fun main() {

    var distancia = 240
    
    var consumo = 12

    var litros = distancia/consumo

  print(litros)
}

____________________________________________________________________________________________________________________________

# Exercicio 5:
    fun main() {

    var valor_prestacao = 500
    
    var meses_atraso = 2

    var taxa_juro = 2
    
    var valor = valor_prestacao + taxa_juro * meses_atraso

  print(valor)

}

____________________________________________________________________________________________________________________________

# Exercicio 6:

    fun main() {
    
    var a = 5
    
    var b = 10
    
    var troca = a
    
    a = b
    
    b = troca
    
    
print(troca)
   
   
}

____________________________________________________________________________________________________________________________

# Exercicio 7:

    fun main() {
    
    var V1 = 1
    
    var V2 = 2
    
    var V3 = 3
    
    var V4 = 4
    
    
println("adições: ${V1 + V2} ${V1 + V3} ${V1 + V4} ${V2 + V3} ${V2 + V4} ${V3 + V4}")

println("multiplicações: ${V1 * V2} ${V1 * V3} ${V1 * V4} ${V2 * V3} ${V2 * V4} ${V3 * V4}")
    
}

____________________________________________________________________________________________________________________________

# Exercicio 8:

    fun main() {
    
    var com = 5
    
    var largura = 3
    
    var altura = 2
    
    var resultado = com * largura * altura
    
print(resultado)
}
    
____________________________________________________________________________________________________________________________

# Exercicio 9:

    fun main() {
    
    var valor_numérico_inteiro = 5
  
println("multi: ${valor_numérico_inteiro * valor_numérico_inteiro}")

}

____________________________________________________________________________________________________________________________

# Exercicio 10:

    fun main(){
    
    var valor1 = 10
    
    var valor2 = 5   

    var resultado = valor1 - valor2

println(resultado)

}
____________________________________________________________________________________________________________________________

# Exercicio 11:

    fun main(){
    
    var dolar = 10
    
    var real = dolar / 5.60    

println(real)

}
____________________________________________________________________________________________________________________________

# Exercicio 12:

    fun main(){
    
    var real = 100
    
    var dolar = real * 5.60    

println(dolar)

}
____________________________________________________________________________________________________________________________

# Exercicio 13:
     fun main() {

    fun Int.aoQuadrado(): Int = this * this
    
    var valor_numérico_inteiro1 = 2
    var valor_numérico_inteiro2 = 3
    var valor_numérico_inteiro3 = 4
  
println("Quadrado:${valor_numérico_inteiro1.aoQuadrado()} ${valor_numérico_inteiro2.aoQuadrado()} ${valor_numérico_inteiro3.aoQuadrado()}")
println("Soma:${valor_numérico_inteiro1.aoQuadrado()} + ${valor_numérico_inteiro2.aoQuadrado()}  ${valor_numérico_inteiro3.aoQuadrado()} ${valor_numérico_inteiro3.aoQuadrado() + valor_numérico_inteiro2.aoQuadrado() + valor_numérico_inteiro1.aoQuadrado()}")
}

____________________________________________________________________________________________________________________________

# Exercicio 14:
    fun main(){
    
    var valor1 = 10
    
    var valor2 = 10

    var valor3 = 10    
    
    var resultado = valor1 + valor2 + valor3   
    
    var quadradoDaSoma = resultado * resultado

println(quadradoDaSoma)

}

____________________________________________________________________________________________________________________________

# Exercicio 15:

    fun main() {
    
    var n = 2
    
    var n2 = 3
    
    var n3 = 4
    
    var n4 = 5
    
    
print("result:${n * n3} ${n2 + n4}")

}

____________________________________________________________________________________________________________________________

# Exercicio 16:

    fun main() {
  
    var mensal = 1000
    
    var porcenagem = 10
    
    var calculo = mensal * porcenagem / 100
   
print(calculo)

____________________________________________________________________________________________________________________________

# Exercicio 17:

     fun main() {
     
    var pi = 3.14159
    
    var raio = 5
    
    var result = pi * raio * raio
    
    
print(result)
}

____________________________________________________________________________________________________________________________

# Exercicio 18:
    fun main(){
        
     var votos_validos1 = 50    
    var votos_validos2 = 60      
    var votos_nulos = 34
    var votos_branco = 17  
    var candidato1 = votos_validos1
    var candidato2 = votos_validos2   
    
    var resultado = votos_validos1 + votos_validos2 + votos_nulos + votos_branco   
    var porcentagem1 = resultado / votos_validos1    
    var porcentagem2 = resultado / votos_validos2    
    var fim = porcentagem1 +  porcentagem2     

 println(fim)

____________________________________________________________________________________________________________________________

# Exercicio 19:

    fun main() {
    
    var v1 = 10
    
    var v2 = 5
 
    
 print("result:${v1 + v2} ${v1 + v2} ${v1 * v2} ${v1 / v2}")
}
____________________________________________________________________________________________________________________________

# Exercicio 20:

    fun main(){
    
    var distancia = 100
    
    var tempo = 2
    
    var velocidade = distancia / tempo / 3.6    

println(velocidade)

}

____________________________________________________________________________________________________________________________

# Exercicio 21:

     import kotlin.math.pow
     fun main() {
   
    var base = 5.0
    var expoente = 2.0
   
    var potência= base.pow(expoente)

print(potência) 
    
}

____________________________________________________________________________________________________________________________

# Exercicio 22:
    fun main() {

    val raio = 5.0
    val pi = 3.1416

    val volume = (4.0 / 3.0) * pi * (raio * raio * raio)

println(volume)
}

____________________________________________________________________________________________________________________________

# Exercicio 23:

    fun main() {
    
    var pes = 10

    var re = pes * 0.3048
    
print(re)
}
____________________________________________________________________________________________________________________________

# Exercicio 24:
    import kotlin.math.pow
    fun main() {
   
    var base = 16.0
    var índice = 3.0
   
    var raiz = base.pow(1.0 /índice)
print(raiz) 
    
}

____________________________________________________________________________________________________________________________

# Exercicio 25:
    fun main() {
   
    var numéro_inteiro = 5
    
    var sucessor = numéro_inteiro + 1
    var antecessor = numéro_inteiro - 1
    
print("Sucessor: $sucessor\nAntecessor: $antecessor")

    
}

____________________________________________________________________________________________________________________________

# Exercicio 26:
    fun main() {
    println("Digite 4 números:")

    for (i in 1..4) {
        val n = readLine()!!.toInt()
        if (n % 2 == 0 && n % 3 == 0) {
println(n)
        }
    }
}

____________________________________________________________________________________________________________________________

# Exercicio 27:
    fun main() {
   
    var numéro1 = 20
    var numéro2 = 8
    
    var resultado = numéro1 - numéro2
   
    
print(resultado)

    
}

____________________________________________________________________________________________________________________________

# Exercicio 28:

    fun main() {

    val numero = 0

    if (numero > 0) {
        println("Positivo")
    } else if (numero < 0) {
        println("Negativo")
    } else {
        println("Neutro")
    }
}

____________________________________________________________________________________________________________________________

# Exercicio 29:
    fun main() {
   
    var nota1 = 6
    var nota2 = 5
    var nota3 = 3
    var nota4 = 4
    
    var media = (nota1 + nota2 + nota3 + nota4) / 4
    if ( media >= 5) {
        println("Aprovado")
    } else {
        println("Reprovado")
    }
   
    
  print(media)

    
}

____________________________________________________________________________________________________________________________

# Exercicio 30:
    fun main() {

    val media = (6.0 + 7.0 + 5.0 + 8.0) / 4

    if (media > 7) {
        println("Aprovado")
    } else {
        val mediaFinal = (media + 6.0) / 2
println(if (mediaFinal > 5) "Aprovado em exame" else "Reprovado")
    }
}

____________________________________________________________________________________________________________________________



