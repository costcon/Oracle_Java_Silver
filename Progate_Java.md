
　Progate Javaコース
  ７月６日〜


Java 学習レッスンⅠ

出力の命令文
System.out.println("Hello World");     //Inではなくln

class Main {                                //クラス部分
  public static void main(string[] args){   //メソッド部分
    System.out.println("Hello World");
  }
}

文の終わりには必ずセミコロン


「データ型について」
Stringのデータ型は大文字、intは小文字



自己代入の省略形

x = x + 10;
↓
x += 10;

※変動する値が１の時のみさらに省略できる

x += 10;
↓
x++;


===============================

変数定義のルール

1number 数字はじまりの変数はエラーになる

first_number スネークケースを使用するのは望ましくない
→userName このように２語以上は大文字で区切る(キャメルケース)

namae
名前.    ローマ字、日本語は望ましくない

===============================


少数を代入するデータ型
double

Javaでは型は自動変換される場合あり

ex1) 5 / 2 = どちらもint型なので小数点以下は切り捨てされ、計算結果はint型の2

ex2) 5 / 2.0 = 片方（もしくは両方）double型の場合は計算結果は2.5

また、手動で計算結果の型を変換したい場合はキャスト（強制的な型変換）を行う

ex) System.out.println((double) 5 / 2);  これによって5がdouble型になるため、計算結果もdouble型になる





