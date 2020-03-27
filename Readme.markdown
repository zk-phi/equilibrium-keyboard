# Equilibrium Keyboard

![eq1](images/eq1.png)

![eq2](images/eq2.png)

コンパクトで透明な 40% キーボードです

アクリル板を積層させて、 5 度の傾斜を持ったケースを構成します。 LED を搭載しているのでよく光ります

また内部の空洞を極力減らした設計により、見た目以上にしっかり重さがあり、音が良いです

ホームポジションがある行に注目すると、ホームポジションがちょうど中央に来る左右対称レイアウトになっています。また両端のキーは 1.25u となっていて、キーボード全体の横幅を小さくしています

上下の段のずれ方は一般的なキーボードと同様になっています

親指キーは自作キーボードらしく多めになっており、ここも左右対称の配列になっています

動作未確認です

# 必要なもの

キット
- トップフレーム 2mm x 2, 3mm x 2
- トッププレート上 (3mm)
- トッププレート下 (2mm)
- ミドルプレート (2mm)
- ボトムプレート上 2mm x 1, 3mm x 1
- ボトムプレート下 (3mm)
- 足プレート 三種類

汎用部品
- キースイッチ, キーキャップ, ダイオード 1N4148w x41
- LED SK6812mini x67
- 2pin タクトスイッチ x1
- Pro Micro
- M2 ねじ 20mm x12, 10mm x3, 8mm x3, 6mm x3
- M2 ナット x21
- 2mm 厚以上のゴムクッション x4

# 組み立て

- 基板にスイッチ以外の部品を実装

ダイオードはコの字の印がカソード、 LED はコの字の印が Vcc

![pcb_backside](images/pcb_backside.png)

- トッププレート上、トッププレート下、基板を重ねて、プレートを挟み込むようにスイッチを実装

![topplates1](images/topplates1.png)

![topplates2](images/topplates2.png)

![switches](images/switches.png)

- (オプション) ボトムプレート下に足プレート３枚を大きい順に取り付け

![bottomplate](images/bottomplate.png)

- ボトムプレート下、ボトムプレート上、ミドルプレート、実装済みの基板、適当な枚数のトップフレームを重ねてねじ止め

ボトムプレート上には 3mm, 2mm の二種類があります。コンスルーの足を切らずに組みたい場合は 3mm を、少しでも薄くしたい場合はコンスルーの足を切って 2mm を選んでください。

トップフレームは見た目と打鍵音のためについているだけなので、好みや手持ちのネジの長さに応じて調整可能です。

![construction1](images/construction1.png)

![construction2](images/construction2.png)

![construction3](images/construction3.png)

![construction4](images/construction4.png)

![construction5](images/construction5.png)

- キーキャップはめてゴム足つければ完成

![construction6](images/construction6.png)

![construction7](images/construction7.png)
