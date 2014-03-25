ECHONETLite-ObjectDatabase
==========================

This repository contains a machine-readable database for [ECHONET Lite](http://www.echonet.gr.jp/english/index.htm) objects (such as home appliances, sensors, and so on,) which is originally generated by [Sony Computer Science Laboratories, Inc](http://www.sonycsl.co.jp/) as a part of [Kadecot project](http://kadecot.net). The database is generated from [the official ECHONET Lite Spec sheet](http://www.echonet.gr.jp/spec/index.htm) and once stored in [Google Drive](https://drive.google.com/folderview?id=0B6eFizhiL1dYNEJqTzJhS1o5aFk). The Google Drive version is reviewed, modified and edited by volunteer experts and exported to CSV files stored in this GitHub repository.
The whole databases (Google Drive version and GitHub version) are distributed under CC0 license. THE DATABASE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED. USE THIS AT YOUR OWN RISK.

本リポジトリは[ECHONET Lite](http://www.echonet.gr.jp/)機器オブジェクト（家電やセンサーなど）の情報、およびそれらのプロパティ情報をプログラムから使いやすいようにデータベース化したもので、[Kadecotプロジェクト](http://kadecot.net)の一環として[ソニーコンピュータサイエンス研究所](http://www.sonycsl.co.jp/)が作成したものが元になっています。データベースは[公式のECHONET Lite規格表](http://www.echonet.gr.jp/spec/index.htm)を[Google Drive上のスプレッドシート](https://drive.google.com/folderview?id=0B6eFizhiL1dYNEJqTzJhS1o5aFk)に変換したものが元となっており、これをボランティアコミュニティがレビュー・修正をほどこしたものをCSV形式にexportしたものです。本データベースはGoogle Driveバージョン、本GitHubバージョン共にCC0ライセンスとなっていますので、著作権を気にせず自由にお使いいただくことができます。本データベースは現状通りで提供されるものであり、いかなる保障もありませんので、ご自身の責任においてお使いいただく必要があることに留意してください。

#Version

24 March 2014  Suports APPENDIX, Detailed Requirements for ECHONET Device Objects, Release C

#Users

[OpenECHO](https://github.com/SonyCSL/OpenECHO) by Sony CSL, an open source ECHONET Lite driver library, utilizes this database for generation device object class codes.

#License

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="https://github.com/SonyCSL/ECHONETLite-ObjectDatabase">
    <span property="dct:title">Sony Computer Science Laboratories, Inc</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">ECHONETLite-ObjectDatabase</span>.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="JP" about="https://github.com/SonyCSL/ECHONETLite-ObjectDatabase">
  Japan</span>.
</p>

#We need your help!

If you find this database useful, please consider volunteering for improvements!
We welcome your help in three aspects below.

1. Report bugs or suggest improvements on [Issues page](https://github.com/SonyCSL/ECHONETLite-ObjectDatabase/issues), or directly apply your modification to the database to send the [pull request](https://github.com/SonyCSL/ECHONETLite-ObjectDatabase/pulls) to this repository.
2. Let us know the link to your application that uses this database by posting an email to <img src="http://kadecot.net/media/email.png" align="center"></img>
Your link will be listed in the #Users section above.
3. Participate in editing the source data on [Google Drive](https://drive.google.com/folderview?id=0B6eFizhiL1dYNEJqTzJhS1o5aFk). Request the invitation by posting an email to <img src="http://kadecot.net/media/email.png" align="center"></img>

もしこのデータベースがあなたのお役にたてたなら、このデータベースをより良いものにするためのお手伝いをぜひお願いします！
３種類の方法で本プロジェクトに貢献することができます。

1. バグや改善点のアイデアなどを[Issues page](https://github.com/SonyCSL/ECHONETLite-ObjectDatabase/issues)にポストしてください。データベースを直接修正し、[pull request](https://github.com/SonyCSL/ECHONETLite-ObjectDatabase/pulls)を送って頂くことも歓迎します。
2. もしこのデータベースを作ってアプリケーションを作ったら、ぜひ<img src="http://kadecot.net/media/email.png" align="center"></img>までその紹介URLを我々に送ってください！
上記のUsersセクションからリンクを張らせていただきます。
3. 本レポジトリの元となっている[Google Drive上のスプレッドシート](https://drive.google.com/folderview?id=0B6eFizhiL1dYNEJqTzJhS1o5aFk)の編集にご参加ください。参加していただける方はご招待いたしますので、<img src="http://kadecot.net/media/email.png" align="center"></img>までご連絡ください。
