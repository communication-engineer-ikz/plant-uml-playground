# Plant UML Playground
## 概要
https://plantuml.com/ja/

### UML とは
https://www.itsenka.com/contents/development/uml/  
```
UML（Unified Modeling Language）は、様々な開発現場で使用されている設計書の書式を統一する目的で規定された言語で、
1997年にOMG ( Object Management Group ) により標準化されました。

但し、UMLによる標準化はあくまで表記方法であって、開発手法の方法論ではありません。
```

1.  シーケンス図 (Sequence Diagram)  
    https://www.itsenka.com/contents/development/uml/sequence.html  
    ```
    シーケンス図とは、クラスやオブジェクト間のやりとりを時間軸に沿って表現する図です。
    機能ごとに相互作用（Interaction）と呼ばれる下記のようなフレーム内に処理内容を記述します。
    ```

1. 状態マシン図 (State Machine Diagram)  
    https://www.itsenka.com/contents/development/uml/state_machine.html  
    ```
    状態マシン図とは、オブジェクトの状態遷移を表現する為の図です。
    各状態の内容および、状態遷移の条件等を記述します。
    ```

1. アクティビティ図 (Activity Diagram)  
    https://www.itsenka.com/contents/development/uml/activity.html  
    ```
    アクティビティ図とは、連続する「実行」の遷移、つまり一連の｢手続き｣を表現するための図です。
    ある事象の開始から終了までの機能を実行される順序にしたがって記述します。 
    状態マシン図が実体の状態遷移を表すのに対し、アクティビティ図では実体の制御の流れを描写します。
    ```


## セットアップ
https://qiita.com/couzie/items/9dedb834c5aff09ea7b2

1. Install VSCODE.  
    https://code.visualstudio.com/

1. Install Graphviz.  
    http://www.graphviz.org/download/#mac  

    - 入れ忘れるとシーケンス図以外の描画ができない。
        ```
        Dot Executable: null
        No dot executable found
        Cannot find Graphviz. You should try
        ```  

    - 参考  
        https://www.hanachiru-blog.com/entry/2019/12/13/203233  
        https://confrage.jp/cannot-find-graphviz-you-should-try/diag-a15bbf618c8c5d64fc03a914cc5d21a0-3/

1. Install PlantUML Plugin.  
    https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml
