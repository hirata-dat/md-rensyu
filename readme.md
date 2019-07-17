# 見出し1

見出し1
===

パラグラフ＝段落＝ｐタグ
改行＝ｂｒタグ＝半角スペース２つ以上

hello.  hello.  
hello.  hello.  
hello.  hello.    

> hello.hello.hello.

##区切り線

---

- ハイフン3つ

---

- アンダースコア3つ

___

- アスタリスク

***

- ハイフンスペース



## 見出し2

### 見出し3

#### 見出し4

##### 見出し5

###### 見出し6

- Item1
- Item2
- Item3  
hello.hello.  
hello.hello.hello.hello.





#強調  
*hello.hello.hello.*  
__hello.hello.hello.__  
***hello.hello.hello.***


*日本語は斜体にならないことが多い*


#ナンバリング

1. Item1
1. Item2
1. Item3

#　ハイパーリンク
- https://tanakaedu.github.io/dat-works/index.html
- [ドットインストール](https://tanakaedu.github.io/dat-works/index.html)  
[ドットインストール](https://tanakaedu.github.io/dat-works/index.html"学習動画サイト"")  
[区切り線](https://github.com/dat19/design)
- 作成したGitHhubのマークダウンの見出しにカーソルを合わせて、左のリンクアイコンを右クリックして、**リンクのコピー**で、その項目を直接開くリンクが得られる

#コード

- バックコートは、[Shift]+[@]キー  
- バッククォー３つの後ろに、言語を指定できる  
　- csならc#  
  - cならc言語  
  - java   
  - スペースなければ戻る



'''cs  
function x(){
  Debug.Log("hello.");
}  
'''

- インラインは、バッククォートで囲う。'Debug.Log()'はデバック表示      

#画像

![画像](figure_barrier_hemisphere.png)  

|列見出し1|列見出し2|列見出し3|
|:---|:---:|---:|
|左揃え|中央揃え|右揃え|
|0|data|data|

- 1行目が行見出し
- 2行目に、列の揃えを指定。:とハイフン1つ以上
  - :--- 左揃え(:か-のみでも左揃え)
  - :---: 中央揃え
  - ---: 右揃え
- 3行目以下が、データ行
