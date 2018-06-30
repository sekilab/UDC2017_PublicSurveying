# Ubiquitous Surveying 暮らしを支える公共測量
<br><br>

## 公開するデータの概要

このページでは，国土地理院の技術資料の一つである「公共測量の記録」を電子化し，各種分析等に利用可能な形にした電子データ(csv形式)を公開しています．<br>
「公共測量の記録」は，前回の東京オリンピックの開催された昭和39(1964)年から発行されており，日本で行われている測量の大半を担う公共測量の基本的な情報を示しています．<br>
しかしながら，平成13(2001)年度までは紙媒体により発行され，その後はPDF形式で公開されているため， 直接分析を行うことは困難でありました．<br><br>
今回公開する，「公共測量の記録」は日本の測量の実態を伝える貴重な資料であり，これを利用した分析が進むことで，この国土において行われた測量，そしてこの国土を去来した測量人の活躍について，より多くの人に知っていただく一助となることを願っています．<br>

## 電子化に用いた資料

国土地理院技術資料  
資料番号：A2-9bからA2-60  
「公共測量の記録」昭和39(1964)年度から平成27(2015)年度  

・平成13年度以降は[国土地理院ウェブページ上](http://psgsv2.gsi.go.jp/koukyou/record/record.html "link title 国土地理院ウェブページ上")で公開されています．<br>
・技術資料については，以下を参照：[国土地理院 技術資料リスト-1](http://www.gsi.go.jp/REPORT/TECHNICAL/gsigijutsu1.htm#koukyou "link title 国土地理院 技術資料リスト-1")<br><br>

## このページで公開しているデータ

* このリポジトリでは，(1)原資料を電子化したデータと(2)分析用に加工したデータの2種類のデータを公開しています．
* このうち，(1)のデータは，紙媒体で発行されてきた昭和39年度から平成12年度を対象に原資料の形式を維持したものです．
* 一方，原資料では不備(地名のミスなど)があったり，フォーマットが不統一であったりするため，それらを修正したものを(2)として公開しています．以下では，(2)分析用データについて説明します．<br>


## データのフォーマット
  
* 「事業量」の単位は，以下のように表記してあります．  
<table>
  <tr>
     <td>原資料中の表記</td>
     <td>ファイル中での表記</td>
  </tr>
  <tr>
     <td>点</td>
     <td>point</td>
  </tr>
  <tr>
     <td>km</td>
     <td>km(そのまま)</td>
  </tr>
  <tr>
     <td>㎢</td>
     <td>KM2</td>
  </tr>
</table>

<br>
## 複数記載がある場合

原資料で，一つの事業につき複数の記載がある場合，以下のように対応しています．  

・「測量地域」については，複数市町村の記載がある場合，それぞれを","(半角カンマ)で区切ってあります． <br>
  また，「一部」と「全域」については区別なくカンマで区切ってあります．<br>
　複数都道府県にまたがる場合は，都道府県が変わって初めて記載されている市町村名の頭に「県境」と記入し，<br>
 「都道府県名」にも同様に「県境」と記入してあります(以下例)．  
 　  
   <table>
   <tr>
      <td>都道府県名</td>
      <td>測量地域</td>
   </tr>
   <tr>
      <td>青森県県境宮城県</td>
      <td>六ケ所村,三沢市,県境大和町,鳴瀬町</td>
   </table>
 
・ 「測量種別」「事業量」については","(半角カンマ)で，「縮尺・等級」については",,"(半角カンマ2つ)で区切ってあります．<br>

## 原資料との異同

* 原資料中には，地名の表記ミスや都道府県-市町村名の対応のミスなどがあったほか，測量地域が複数都道府県にまたがる  
にも関らず，一つの都道府県のみ記載されている場合がありました．こうした問題に対して，公開しているファイルでは  
地名の修正を行った他，測量地域に対応する様に都道府県を追記しています．<br>
* なお，「測量地域」の項では，原資料では「市町村名」，「市町村名+一部」，「市町村名+全域」となっている場合が混在しており，表記の統一のためにこれらは削除してあります．<br>

## 公開ファイルに関する諸注意

公開しているファイルのうち，以下の点については注意して使用してください．

1. 原資料中でパンチングされているなどして，資料の一部に欠損がある場合があります．ご注意ください．
2. 平成13(2001)年度以降は，公開されているPDFファイルを市販のソフトウェアで変換し，残ったスキャンミスを手動で<br>
　修正しましたが，このうち研究で使用しない「測量目的」「計画機関」「作業機関」「自至時期」については<br>
　修正の対象外としたため，スキャンミスなどが含まれていることが予想されます．<br>
3. この他，年度や記録による細かい書式の異同等は全て統一してあります．<br>
  
## 利用にあたって

このページで公開されているデータは <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">クリエイティブ・コモンズ 表示 4.0 国際 ライセンス</a>の下に提供されています。<br><a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />

従って，以下のような形で出典を明記していただければ，どなたでもご自由にお使いいただけます．<br>
・国土地理院の技術資料であることを明記すること(国土地理院の規約に準ずること)<br>
・東京大学生産技術研究所関本研究室が加工・作成したものであること<br><br>
例)<br>
国土地理院技術資料「公共測量の記録　昭和/平成○○年度」(資料番号：●●)をもとに東京大学生産技術研究所関本研究室が加工したデータを利用した<br>
URL:https://github.com/sekilab/UDC2017_PublicSurveying
<br>
## 免責について

・東京大学生産技術研究所関本研究室は，利用者が本ページで公開されているデータを用いて行う一切の行為について，何ら責任を負いません．<br>
・公開されているデータは，予告なく変更・削除等が行われることがあります．<br>
