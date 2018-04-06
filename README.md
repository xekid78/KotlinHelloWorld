# KtHelloWorld
HelloWorldと表示

## 処理
画面に`HelloWorld`と表示

## コード
```
package com.example.mako1.myapplication

import android.support.v7.app.AppCompatActivity
import android.os.Bundle

class MainActivity : AppCompatActivity() {

    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)
        println("Hello World")
    }
}
```

## 出力結果  
![Android Studio画面](https://imgur.com/a/kiT2D "Android Studio")
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 統合開発環境(IDE) | Android Studio 3.1 |
| 開発言語 | Kotlin 1.2.31 |
