
class Arithmetic{
    var number1:Int=0
    var number2:Int=0
    fun add(num1:Int,num2:Int){
        number1= 20
        number2=10
        var answer:Int=number1+number2
        println("The sum is:${number1+number2}");
    }
    fun subtract(num1:Int,num2:Int){
        number1 = 20
        number2 = 10
       var answer1:Int= number1-number2
        println("The difference is:${number1-number2}")
    }
    fun multiply(num1:Int,num2:Int){
        number1=20
        number2=10
        var answer2:Int= number1*number2
println("The product is:${number1*number2}")
}}
fun main(args:Array<String>) {
    Arithmetic()
    var ari = Arithmetic()//create ari object of Arithmetic class
    ari.add(20, 10)
    var arib = Arithmetic()//create arib object of Arithmetic class
    arib.subtract(20, 10)
    var aric = Arithmetic()
    aric.multiply(20, 10)
}
