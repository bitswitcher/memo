## 見出し
\# を見出しにしたい箇所の行頭につけます。

    # 見出し1です
    ## 見出し2です
    ### 見出し3です
    #### 見出し4です
    ##### 見出し5です
    ###### 見出し6です

## 改行
改行したい箇所に**半角スペースを２つ**つける。
 
## 強調
**強調したい**箇所の前後に**をつける。

    **強調したい**

## 斜体
*斜体にしたい*箇所の前後に*をつける。

    *斜体にしたい*

## リスト
リストには番号付き、番号なしの２種類がある。

    番号なし
    - 番号なしリスト
    - 番号なしリスト 

    番号あり
    1. 番号ありリスト
    2. 番号ありリスト

## 打ち消し線
打ち消し線は~~打ち消したい~~箇所の前後に ~~ をつける。

    ~~打ち消したい~~

## 引用
> 引用は引用したい箇所の行頭に > をつける。

    > ここから引用
    >> さらに引用
    >>> もっと引用

## リンク
URLのリンクは[Onkyo HP](http://www.jp.onkyo.com/)と書く。
相対パスは[Cirrus DSP](../memo/dsp/cirrus/Cirrus_DSP_Index.md)と書く。

    [Onkyo HP](http://www.jp.onkyo.com/)
    [Cirrus DSP](../memo/dsp/cirrus/Cirrus_DSP_Index.md)


## インラインコード
文中の変数`param1`やコード`print`などは ` を前後につけると読みやすくなる。

    `param1`  
    `print`


## コードブロック
ブロックとは灰色の枠で文章を囲むこと。  
コードブロックはコードを ``` で囲む。  
また囲むとき、言語を指定するとGitHubやBitbucketでシンタックスがハイライトになる。  
**対応していない言語もあるので指定しなくても構わない。**

```c
#include <stdio.h>
int main(void)
{
  int x = 0, y = 1;
  return (x + y);
}
```

```ruby
class RubyClass
  def ruby_method
    "ret"
  end
end
```

## 区切り線
3つ以上のハイフン - アスタリスク * アンダースコア _ だけで構成されている行は罫線になる。
___


    ------------------------------------
    ********
    _________

## 画像
Inline-style:  
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style:  
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

## テーブル
| Left align | Right align | Center align |
|:-----------|------------:|:------------:|
| This       |        This |     This     |
| column     |      column |    column    |
| will       |        will |     will     |
| be         |          be |      be      |
| left       |       right |    center    |
| aligned    |     aligned |   aligned    |

```
| Left align | Right align | Center align |
|:-----------|------------:|:------------:|
| This       |        This |     This     |
| column     |      column |    column    |
| will       |        will |     will     |
| be         |          be |      be      |
| left       |       right |    center    |
| aligned    |     aligned |   aligned    |
```

