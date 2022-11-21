val names : List[String] = List("Leo", "Cristiano", "Ener", "Felipe")
names.map(_.length())

val numbers = List(3, 4, 7,11,  12)
val isPrime = (nro: Int) => (2 to nro -1).forall(nro % _ != 0)
numbers.map(isPrime(_)match{
    case true => 1
    case false => 0
}).sum

val numbers2 = List(6, 28, 15, 12, 11, 24)
numbers2.max
numbers2.min
numbers2.size

def isPrime1(nro : Int) : Boolean = (2 until nro).forall(nro %_ != 0)
def isPrime2(nro : Int) : Boolean = (2 until nro).exists(nro %_ != 0)

List(1,2,3,4,5).filter (k => k%3 != 0)
List(1,2,3,4,5).takeWhile (k => k%3 != 0)

def divP = (n : Int) => (1 until n).filter(div => n% div == 0)

divP(6).sum
val number = List(6, 28, 15, 12, 11, 24)
val sumDiv = (nro : Int) => (1 until nro).filter(div => nro % div == 0).sum
number.filter(nro => nro == sumDiv(nro)).size

def !!(n : Int) : Int = {
    n%2 match{
        case 0 => (2 to n by 2).product
        case _ => (1 to n by 2).product
    }
}
!!(5)
!!(8)

val numbers3 = (1 to 20).toList
numbers3.filter(nro => nro % 2 == 0).size
numbers3.count(nro => nro % 2 == 0)
def contarPrimos(nros : List[Int]) : Int = {
    val isPrime3 = (n : Int) => (2 until n).forall(n % _ != 0)
    nros.count(isPrime3)
}
contarPrimos(numbers3)

def tresFactores(nros : List[Int]) : List[Int] = {
    val Factores = (n : Int) => (2 until n).filter((n % _ == 0))
    nros.filter(nro => Factores(nro).size == 3)    
}
tresFactores((1 to 900).toList)
