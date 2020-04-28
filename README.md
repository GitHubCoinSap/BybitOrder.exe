# BybitOrder.exe
![image](https://user-images.githubusercontent.com/43275193/72671548-87b8f000-3a8f-11ea-8ffc-efa0db7ae510.png)  
  
**<a href="https://github.com/GitHubCoinSap/BybitOrder.exe/releases/latest" target="_blank">ダウンロードはここから</a>**
  
**<a href="https://www.youtube.com/watch?v=EHruFNfvnxo" target="_blank">自動追従動画はここから</a>**  
**<a href="https://youtu.be/WRyNIqTpxgY" target="_blank">English movie.</a>**  
**<a href="https://youtu.be/WRyNIqTpxgY" target="_blank">简体中文 视频</a>**  
**<a href="https://youtu.be/hQYReJAsKww" target="_blank">繁體中文 視訊</a>**  
**<a href="https://youtu.be/LpuH4MHHRv4" target="_blank">한국어 동영상</a>**  
  
Bybit注文ツール　BybitOrder.exeは、注文をより簡単に行うツールです。  
  
**<a href="https://www.bybit.com/home/jp/index.html?affiliate_id=538&group_id=1254&group_type=1" target="_blank">Bybit登録</a>から新規にBybitに登録した方は無料でお使いいただけます。 ** 
※既にBybitに登録済みの方で使用したい方は、後述の「ツール購入方法」を参照してください。
  
**利用にあたっては、BybitのUIDを登録する必要があります。**  
UIDの登録は、Twitterで、<a href="https://twitter.com/coin_sap" target="_blank">@coin_sap</a>までDMでご連絡をお願いします。  
登録完了はDMでの返信となります。  
**一度登録すると、今後のバージョンアップに対しても永続的に利用できます。**  
  
<a href="http://coinsap.php.xdomain.jp/bybitorder/rule.html" target="_blank">利用規約</a>を読んだ上で、ByBitOrder_X.X.X.X.zipを
<a href="https://github.com/GitHubCoinSap/BybitOrder.exe/releases/latest" target="_blank">ダウンロード</a>して使用してください。
  
<a href="http://coinsap.php.xdomain.jp/bybitorder/index.html" target="_blank">操作説明書</a>は同梱していませんので、リンクより参照してください。  
  
**※BitMEX版は<a href="https://github.com/GitHubCoinSap/BitMexOrder.exe" target="_blank">こちら</a>**  
  
動作環境  
・Windows10　64bit  
・.NET Framework 4.8以降  
  
・ツール購入方法  
　価格は0.02BTCです。
※2020.01.12～（**BTCの大幅な価格変動や大幅な機能追加があった場合には改訂します**）  
　永続利用なので、早めの方がお得かと思います。
 
　ウォレットアドレス　：　14f29qWhrmMETBJudTf7tAhHiaaQhKWuMp  
　に送金後に、送金元ウォレットアドレスとBybitのUIDをTwitterで、<a href="https://twitter.com/coin_sap" target="_blank">@coin_sap</a>までDMでご連絡をお願いします。  
  
リリース 
V1.0.0.14  2020.04.11  
・한국어  
・繁體中文  
言語追加  
  
V1.0.0.13  2020.04.05  
・English  
・简体中文  
言語追加  
  
V1.0.0.12  2020.03.29  
・設定保存の不具合修正  
  
V1.0.0.11  2020.03.25    
・注文がキャンセル（PostOnly時）された時にも追従継続するように修正。  
・注文数＄0のチェックを追加。  
・板の更新間隔をスライダーで１０秒まで任意に変更できる機能の追加。  
・GPU使用の不具合の修正。  
※GPU利用の場合は、別途「CUDA Toolkit 10.2」をダウンロードしてください。インストール時にVisual Studioに関するエラーが発生しても問題ありません。
**<a href="https://developer.nvidia.com/cuda-downloads?target_os=Windows&target_arch=x86_64&target_version=10&target_type=exenetwork" target="_blank">CUDA Toolkit 10.2 ダウンロード</a>**  
    
V1.0.0.10  2020.02.18  
・設定項目に「開始と同時に板表示」を追加  
・画面の初期表示位置を前回閉じた位置にする  
・最終取引ペアを次回の初期表示ペアにする  
・ByBitOrder.exe.configの設定値を別の場所に保存することで、上書きを気にしなくても良くなった  
  
V1.0.0.9  2020.02.16  
・枚数指定とUSD指定の上限の拡大  
  
V1.0.0.8  2020.02.15  
・ETH/EOS/XRPでの指値取得がBTCになっていた不具合の修正。  
  
V1.0.0.7  2020.02.15  
・$100,000になっても良いように、表示枠拡大。  
・ETH/EOS/XRPが板も含めて全対応。  
  
V1.0.0.6  2020.02.11  
・先頭板追従時の成行に変わるまでの回数の設定が保存されていなかったために次回起動時には１０に戻っていた。  
・先頭板追従時の成行に変わるまでの回数の初期値を0に変更。（約定まで追従を続ける）  
  
V1.0.0.5  2020.02.01  
・NVIDIA製GPUがあれば、板表示高速化  
  
V1.0.0.4  2020.01.28  
・板画面のコンパクト化  
・板表示範囲の固定機能  
ウィンドウサイズを縦に伸ばすことで、表示範囲を広げることもできます。  
  
V1.0.0.3  2020.01.24  
・全建玉決済ボタンの追加  
急激な取引量増加で、急いで決済したいときに使用します。  
危険なボタンなので、有効無効が切り替えられます。  
  
V1.0.0.2  2020.01.20  
・バージョンアップ通知  
・指値直接入力時にBTC枚数計算を現在価格から、指定価格に変更  
  
V1.0.0.1  2020.01.19
・板取引からの指値注文  
  
V1.0.0.0  2020.01.12  
・初リリース  
