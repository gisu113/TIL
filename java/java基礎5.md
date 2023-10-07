- 切り捨て、切り上げ、四捨五入
public class P142_1 {
    public static void main(String[] args){
        double d1 = 11.8;
        System.out.println("切り捨て: " + Math.floor(d1));
        System.out.println("切り上げ: " + Math.ceil(d1));
        System.out.println("四捨五入: " + Math.round(d1));
    }
}
