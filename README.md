# davaleba-1
import java.util.Date
fun main(){
    //დავალება 1
    //mean(mutableListOf(1, 2, 3, 4, 5, 6, 7, 8, 9, 10))
    //დავალება 2
    //checkString("pop")
    //checkString("abcd")
    //დავალება 3
    //date()
}
//დავალება 1
fun mean(mutableList: MutableList<Int>) {
    var x: Int = 1
    var index: Int = 0
    var sum: Int = mutableList[0]
    for (i in mutableList) {
        index++
        if (index % 2 == 0) {
            x ++
            sum += mutableList[index]
        }
        if (index==mutableList.size-1) break
    }
        println(sum/x)
}
//დავალება 2
fun checkString(s: String) {
    if (s==s.reversed()) println(true)
    else println(false)
}
//დავალება 3
fun date(){
    var d:Date=Date()
    println(d)
}
