# lecture documents in 2024 / 授業(群)のテキストなど

- We distribute documents e.g. Text, Worksheets and et.al. here.
- 授業(群)のテキストなどを配布するサイトです
     - 基本的に情報システム工学科3年生むけのコンテンツです
     - [C言語 - プログラミングの基礎は、すべてジャンケンとモグラ叩きが教えてくれた C言語編 -](clang/)だけは2年生向けです(なぜ「C言語編」というタイトルなのか?というと、
     [C言語](clang/)、
     シェル、
     [Perl](https://unix-entrance.fml.org/perl/)、
     [Go言語編(インフラチームの研修兼)](https://lectures.fml.org/slides/training/infra-bootcamp/)があるからだ:-)

## 情報システム開発基礎演習 インフラ編 (#01-#06)

- [インフラ編のスライド(第01-06回 合併版)](skill-intro/情報システム開発基礎演習（2024）_インフラ編.pdf)


## コンピュータネットワーク

- [スライド 第01-08回 合併版](skill-network/network-2024-text_01-08.pdf) ... ネットワーク基礎知識編
    - [動画(Youtube再生リスト)](https://www.youtube.com/playlist?list=PLS2cEmI21XYI0JwmLPz4uddf4eKtWRUwX)
- [スライド 第10-13回 合併版](skill-network/network-2024_設計編.pdf)     ... ネットワーク設計演習編
- 設計演習編(第10-15回)の資料
    - [設計ガイド](skill-network/network-2024_設計ガイド_20220721.pdf)
    - [原価表](skill-network/network-2024_原価表_20220705.pdf)
    - [FAQ(よく聞かれる質問とその回答)](skill-network/network-2024_FAQ_20220705.pdf)
    - [見積り例](skill-network/network-2024_見積りの例_20220705.pdf)
    - [提案書のテンプレート](https://docs.google.com/presentation/d/1pgMNGudMf0w62pDAg3KpnDutECviRNVBOt0JKlShCaQ/edit?usp=sharing)
        - Google Slideです。好きなフォーマットでダウンロードして使ってください
    - 提案書の P.11 に登場する物理構成図の元ネタ	
        - [libreoffice format](skill-network/network-2024_構成図テンプレート.odg)
        - [png format](skill-network/network-2024_構成図テンプレート.png)


## クラウドコンピューティング

- [スライド 第01-08回 合併版](skill-cloud/SKILL-CLOUD_01-08.pdf) ... Unixタイムシェアリングシステムの基礎概念(1)権限(2)階層
    - [動画(Youtube再生リスト)](https://www.youtube.com/playlist?list=PLS2cEmI21XYLeOvQ4eGTLbYWrbBpyZIjt)
- [スライド 第10-12回 合併版](skill-cloud/SKILL-CLOUD_10-12.pdf) ... クラウドサービスの基礎
- 補足資料
    - [WWWの基礎](skill-intro/SKILL-INTRO_WWW.pdf)
    - [HTMLの基礎](skill-intro/SKILL-INTRO_HTML.pdf)
    - [EC2の作成](skill-intro/SKILL-INTRO_EC2.pdf)
    - [EIP(Elastic IP)を付ける](skill-intro/SKILL-INTRO_EIP.pdf)
    - [ELBの設定](skill-cloud/SKILL-CLOUD-AUX_AWS-ELB.pdf)
    - [www.pyを改造してキャッシュ(Redis)に値を保存する](skill-cloud/SKILL-CLOUD-AUX_Redis.pdf)



## 参考資料

### ITインフラ初心者向けLPI Webinar(2024-06-08開催)より

- [スライド](https://speakerdeck.com/fmlorg/burauzanohutawokai-ketehttpti-yan-siyou-20240608v1-dot-0-0)
   - 情報システム工学科3年生の「実務を全力でやるITインフラストラクチャ演習群」からの抜粋になっています。
   - [Bパートのハンズオン](https://speakerdeck.com/fmlorg/burauzanohutawokai-ketehttpti-yan-siyou-20240608v1-dot-0-0?slide=10)(動画8:45-51:35,スライドp.10-48)は復習にどうぞ
   - [Cパートのキャリア形成](https://speakerdeck.com/fmlorg/burauzanohutawokai-ketehttpti-yan-siyou-20240608v1-dot-0-0?slide=50)についてのコラム(動画51:35-,スライドp.50-)は研究室紹介総論も兼ねています。
     いや、むしろCパートがメインか？Cパートは(ITインフラに限らず)エンジニア全般および学生向けのつもり


### Unixとコンピュータ開発史(超概論)

- タイトル: シェルとPerlの使い分け、 そういった思考の道具は、どこから来て、どこへゆくのか？
- [スライド](https://speakerdeck.com/fmlorg/sierutoperlnoshi-ifen-ke-souitutasi-kao-nodao-ju-ha-dokokaralai-te-dokoheyukunoka-v1-dot-1-0)
    - [YAPC::Hakodate 2024](https://yapcjapan.org/2024hakodate/)での招待講演
        - YAPC(Yet Another Perl Conference)
        - 2024-10-05 公立はこだて未来大学
        - twitter のまとめは toggeter をどうぞ ->
	  [[全体]](https://togetter.com/li/2413958)
	  [[track Aのみ]](https://togetter.com/li/2446797)
    - Part A. - E. まで五部構成です、40分に凝縮して話してますけど
        1. [パートA: Unix上で生活する際の「シェルとPerlの使い分け」は？自分の環境と履歴から分析する](https://speakerdeck.com/fmlorg/sierutoperlnoshi-ifen-ke-souitutasi-kao-nodao-ju-ha-dokokaralai-te-dokoheyukunoka-v1-dot-1-0?slide=6)
        1. [パートB: Unixのパイプとは？](https://speakerdeck.com/fmlorg/sierutoperlnoshi-ifen-ke-souitutasi-kao-nodao-ju-ha-dokokaralai-te-dokoheyukunoka-v1-dot-1-0?slide=14)
        1. [パートC: コンピュータ開発史におけるUnixの立ち位置](https://speakerdeck.com/fmlorg/sierutoperlnoshi-ifen-ke-souitutasi-kao-nodao-ju-ha-dokokaralai-te-dokoheyukunoka-v1-dot-1-0?slide=21)
        1. [パートD: コンピュータ開発史: その観念/妄想は、どこから来たのか？(仮説) + お金の話](https://speakerdeck.com/fmlorg/sierutoperlnoshi-ifen-ke-souitutasi-kao-nodao-ju-ha-dokokaralai-te-dokoheyukunoka-v1-dot-1-0?slide=24)
        1. [パートE: ご飯を食べる手段としてのIT産業の未来](https://speakerdeck.com/fmlorg/sierutoperlnoshi-ifen-ke-souitutasi-kao-nodao-ju-ha-dokokaralai-te-dokoheyukunoka-v1-dot-1-0?slide=39)
        1. [おわりに - <B>Free Software, the Endless Frontier</B> -](https://speakerdeck.com/fmlorg/sierutoperlnoshi-ifen-ke-souitutasi-kao-nodao-ju-ha-dokokaralai-te-dokoheyukunoka-v1-dot-1-0?slide=45)
- 動画は、たぶん、現在、編集中だと思います。
  そのうち Youtube で見られるはずです


### 動画

[![ブラウザのフタを開けてHTTP体験しよう](https://img.youtube.com/vi/y84Asag9O1o/maxresdefault.jpg)](https://www.youtube.com/watch?v=y84Asag9O1o)
LPI Webinar 2024-06-05
