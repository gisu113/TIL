- +演算子で変数内の文字列を連結できる
public class StrPlus1 {
    public static void main(String[] args){
        String s1 = "こんにちは";
        String s2 = "Java";
        String s3 = s1 + s2;  //s1とs2を連結してs3に代入
        System.out.println(s3);  //s3を出力
        System.out.println("ようこそ" + s2);  //「ようこそ」とs2を連結して出力
    }
}
