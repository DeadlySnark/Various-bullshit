※このパッチは、未熟者が「あなたが調教される」系に感化され、作成しようと思い至った結果の代物です。
※現状、カウンターセクハラがいくらか多様化した程度にしか効能が現れません。

※「era紅魔館protoNTR0014.1」+「era紅魔館protoNTR0014.1用パッチまとめ140624_1」で、ざっと動作チェックはしてみましたが、まだまだ自信がありません。
※地の文やキャラ口上も多少は用意しましたが、拙い・無駄にくどい・心情分岐が揃っていない・そもそもコレジャナイ等々あると思います。
　ご容赦のほどを。
　改めてみると、処女消失の長いこと、くどいこと


;;----------------------------------------------------------------------------
・肉便器じゃないのに、管理人になられちゃう点を修正
・肉便器が貞操帯を着けてもらったとき、正しく表示されなかった点を修正
・肉便器が、自ら貞操帯を着けられないように修正
　→肉便器のくせに自分の貞操を守ろうとするのも可笑しいと言う建前。本音は、挙動面での競合が……
・パンツの制御を修正
　※パンツも心配ですが、貞操帯や着けっぱアイテム系と、うふふ・押し倒しの摺り合わせが未解決。
　　この辺はベース部分のあちこちに手を入れなきゃ系なので、タイミングを見て一気に直さないと（汗
・「性欲処理（Ｖ＆Ａ）」が正しく機能していなかった点を修正

20140627
;;----------------------------------------------------------------------------
・「アイテムを装着される」系が、正しく動いていなかった
　→アイテムが停止した際の、外してもらう描写が出ないで、即着け直し
　→処女でバイブを買っちゃうと、そもそも発生しない

・「処女献上」時に、女の子がイベント中に[ふたなり]となった際、エラー落ち
　【調教SLG】eratoho総合スレ【ビデオ175$】 >>237（eraT0006698.log）様、報告感謝です
　→類型で、女の子の射精やあなたの絶頂が上手く処理できていなかった点を修正

20140624
;;----------------------------------------------------------------------------
・「Talent.csv」に、「38,管理人」「39,肉便器」を追加。
　→「39,肉便器」は、最初から始めた際の、初期設定でのみ獲得可能な、あなた専用素質としております。
　→「38,管理人」は、上記・肉便器あなたを管理する役目の女性で、紅魔館に住む女性専用としております。（あなた／チルノ／大妖精　は、獲得不可）

　新素質を設定させていただいた理由は、「紅魔館の性欲処理係」と「人里にも解放されている公衆便所」は、別物であると考えたからです。
　むしろ「紅魔館の性欲処理係」が、訪問者さんの手によって公衆便所に堕とされるというのは、一種のＮＴＲであると考えます。
　ですので、別の素質として、初期設定でも[肉便器]と[公衆便所]は同時に設定できないようにしました。
　また[NTR]も、[肉便器]と同時には設定できなくしてあります

　名称を[肉便器]としたのは、他に良いワードを思いつかなかったからです……

・「CFLAG.csv」に、700~731を設定させていただきました。

・本パッチ関連で、下記の既存ERBファイルに手を加えさせていただきました。変更箇所は、[;;]のコメントを置いてあります。
	CLOTHES.ERB
	EVENTTURNEND.ERB
	INFO.ERB
	SHOP_CUSTOM.ERB
	SOURCE.ERB

・存在しなかった「\口上\7_子悪魔\対あなた口上.ERB」を作成させていただきました。
　呼称関連の設定をしておきたかったためです。
　呼称の設定は、小悪魔を見本としています。
　子悪魔が小悪魔を呼ぶ際は「お姉ちゃん」と言わせています。イメージなどに誤りがありましたら、お手数ですが修正をお願いいたします。

・下記ファイル群が追加となります。
	TOILET_COUNTER.ERB
	TOILET_COUNTER_ACTABLE.ERB
	TOILET_COUNTER_COMBINATION.ERB
	TOILET_COUNTER_MESSAGE.ERB
	TOILET_COUNTER_POSE.ERB
	TOILET_COUNTER_PUNISHMENT.EBR
	TOILET_COUNTER_REACTION.ERB
	TOILET_COUNTER_SOURCE.ERB
	TOILET_EVENT_KOJO.ERB
	各キャラ口上に
		WC系口上.ERB

＞＞成したこと
・セクハラ部分に、いろいろと追加。
　→肉便器は、パンツを取り上げられたりします。
　　条件によっては、どんなパンツを穿くか女の子が選んでくれたりします。
　→肉便器は、処女の時に女の子達に奪っていただけます。
　　まず予約が成されて、条件が整うと予約した女の子が奪ってくれます。
　→肉便器は、使っていただく道具を自分で用意させていただけます。
　　通信販売で道具を購入すると、女の子達からされることが増えたりします。
　　現状、ニプルキャップ／クリキャップ／ローター／バイブ／アナルバイブが、対応。おおむね、貞操帯ローターと同じ感じです。
　　また、ペニスバンドかバイブを購入しておくと、ちんこがない女の子に処女を奪ってもらうことが出来たりします。
　などなど

　また、
　→肉便器なので、女の子達のおしっこを飲ませていただけます。
　　……と、やってみたつもりなんですが
　　ぅなパッチに併せたつもりなんですが、ぅなパッチでおしっこするように設定しても、現状だとおしっこしなくないですか？
　　この辺が、まだ未熟者なためによくわかりません。


＞＞成すべきこと、成したいこと
・肉便器側からの、能動的（つまり、コマンドを選択したときに発生する）イベントやリアクションを設けたい。
・訪問者さん関連にも、専用パートを設けたい。訪問者さんからも、セクハラ的なことをされる……みたいな。
・人里に行っただけで、酷い目に遭ったりするイベントとかを設けたい。
・妖精メイドさん達からもいろいろされるようにしてみたい。
　併せて、「各部屋イベント（現状、厨房にあるような」を設けたい。
・肉便器から公衆便所に墜ちたときの、諸々イベントを設けたい。



→「あなた」のイメージ
　面白がったレミリアのおかげで、食料にもならずに、生きていられる。
　そもそも拾われて、状態を見て食料行きだったような感じ？
　紅魔館以外でも、生きる場所はなく、生きる術もなく、生きる価値や権利を認めてもらえなかった。
　人間社会には絶対つきまとう、薄暗くて汚い部分の被害者であると同時に、吹きだまり。
　自分に価値を見出せないのに、便器としての価値を見いだしてもらって、その役目を与えてもらって
　生きていく場所をもらって、食事も出て、寝床もあって、あろうことか自分の部屋が用意されてる！
　……ので、便器として超頑張る。
　とはいえ、動ける・働ける者を、ボケッとトイレに立たせておくのも無駄なので、準メイドとして
　働くように咲夜さんから言われた。
　……という感じでしょうか？
