# Prog2kakushin
# プログラム1について
# 概要
私はテーマが行列である実社会数学の課題をすぐできるようなプログラムを作成しました。事前に距離を計算して、表を作ってもらう必要がありますが、それ以降のグループ化や、デンドログラムの作成はこのプログラムがすべて行ってくれます。
# これを作った理由
実社会数学のグループ課題は手作業でやるとかなり大変です。私自身も、グループ化するたびに値を間違えていないか確認しながらやっていたので、大変でした。そのため、このようなプログラムがあれば、グループ化、デンドログラムの作成が一瞬でできると思い、作ろうと決めました。
# 入力と出力
このプログラムは表を作ってもらう必要がありますが、その表は左右対称でないとエラーが起きます。また、最小値を利用してグループ化しているため、表の中の値よりも大きい値をhazureという変数として表に入れないと、最小値を認識できなくなってしまい、エラーが起きます。このふたつを避ければ、プログラムを実行することができ、グループ化するたびに表を表示し、最後にはデンドログラムを出力してくれます。
# 工夫点
表が左右対称であることを利用して、対角線の位置を把握し、どこまでの値をとるかを決めるというプログラムを入れているのが工夫した点です。グループ化するときに、グループ化する対象の持つ値をリストに入れて、それを比較し、小さい方を新しいリストに入れることで、新しい値をとることができるというプログラムを作成したのも工夫した点です。コンマではなくスラッシュを入れることで、見やすくかつエラーを避けることができるようにしたのも工夫した点です。
# プログラム2について
# 概要
numpyを使って、ゲームを作りました。四つの丸を縦、横、斜めのどれかでそろえると勝利です。またコンピュータはばつを表示します。
# 入力と出力
1~7の数字を選ぶと、その数字の場所に丸を置きます。自分のターンが終わると、コンピュータのターンになり、自動で数字を選びばつを置きます。ターンが終わるごとに盤面を表示します。
# 工夫点
コンピュータは相手がリーチしていれば、それを食い止めるように行動し、自分がリーチになれば勝つように行動する(斜めは除く)よう工夫した。
盤面を表示して見やすくした。プレイヤーが意図しない行動をとった場合プログラムを強制終了するようにした。
