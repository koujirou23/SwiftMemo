### 関数定義の基本
返り値の型指定可能  
値を返さない関数は下記のどれか  
1.「->」と型を省略する  
2.「->()」  
3.「-> Void」  
```
// 基本
func 関数名 (仮引数: 型) -> 型 {
    do anything
}
```
###### 引数ラベルの省略  
```
func area(_ h: Double, _ w:Double) -> Double{
    return h * w
}

// 呼び出し元
let a = area(10.0, 12.5)
```
###### 仮引数の省略
```
// 第3引数を関数で利用しない場合
func compare(_ a:Int, _ b:Int, _:Bool)

// 引数のラベルは指定したい場合
func compare(_ a:Int, _ b:Int, option _:Bool)

// 呼び出し元
compare(10, 8, option:true)
```

