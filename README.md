# akym_lang

## これは何？

思いつきのやつです。やってることは置換して既存のGrassの処理系に投げてるだけです。（そのうち自分で実装する）

## usage

既存のgrassのコードをエンコード

`./akiyama --encode grass_code_flle`

出来たものを実行

`./akiyama yeah_yeah_code`

## sample
`sample/grass_helloworld` にGrassで書かれたhello worldがあるのでそれを変換し、実行してみます。

```
[hoge]$ ./akiyama --encode sample/grass_helloworld > akym_hw # => ウォウとっしーウォウイェイ・・・
[hoge]$ ./akiyama akym_hw 
Hello, world![hoge]$ 
```


## 内蔵のGrass処理系について

Grass開発者のUENO Katsuhiro氏が公開している[ruby版の処理系](http://www.blue.sky.or.jp/grass/doc_ja.html)を動作するように修正して内蔵しています。

### 著作権
内蔵したGrassの処理系の著作権はすべてUENO Katsuhiro氏に帰属しています。
また、免責事項は以下になります。

```
THIS SOFTWARE IS PROVIDED BY THE AUTHOR AND CONTRIBUTORS ``AS IS''
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO,
THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE AUTHOR OR CONTRIBUTORS
BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR
BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE
OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN
IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

Copyright (C) 2006, 2007 UENO Katsuhiro. All rights reserved.
```

