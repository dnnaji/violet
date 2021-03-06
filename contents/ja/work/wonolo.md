---
title: Wonolo
year: 2018
owner: Wonolo, Inc.
role: デザインリード, UX/UI デザイン
related:
  - laughly
  - finery
  - libzcareer
colors:
  - "#f9dd00"
  - "#a5a5a5"
  - "#ffffff"
  - "#f8f8f8"
  - "#5b5b5b"
description: |
  Wonoloは倉庫業務や、配送業務、イベントスタッフといった仕事をパートタイムで探す人と、企業とを繋ぐオンラインスタッフィングサービスです。特徴は、Wonolo経由で仕事をすることでバッジが貯まり、特別報酬がもらえることです。それらをより分かりやすく伝え、プロフィール入力率と仕事の応募率を上げるためにプロフィール画面をデザインし直すことがこのプロジェクトのゴールでした。リサーチャー、デザイナー総勢11人を率いるチームの共同リーダーを務め、情報設計とAndroidアプリのプロトタイプ制作を牽引しました。
---

<work-media name="overview.jpg" alt="提案したWonoloのアプリデザイン" />

このプロジェクトでクライアントに提出した最終デザインの一部です。このデザインに至るまでに、ワイヤーフレームによるUI設計、プロトタイプの制作、2回のユーザーインタビューによる仮説検証を行いました。

## ユーザーインタビューによるリサーチ

Wonoloは毎週ユーザーミートアップを開催しており、私たちはそこでユーザー8人にインタビューを行いました。翌日、ユーザーのペインポイントをポストイットに書き出して、似た意見ごとにグルーピングしました。次に、ビジネスとして重要なことと、ユーザーにとって重要なことに重み付けをし、このプロジェクトで解決すべき問題を議論しました。

<work-media name="research_postit.jpg" alt="リサーチの様子" />

### インタビューで発見した問題点

膨大にあった意見を議論によって絞り込んだ後、その中から更にユーザーの意見が多かった順に並び替えると、大きく分けて4つのユーザーのペインポイントが見えてきました。

1. Requesterと呼ばれる企業の採用担当者に、どのようにプロフィールが表示されるのかを知りたい
1. Wonoloの特徴であるバッジと特別報酬の詳細がよく分からない
1. プロフィールの入力を完了させる目的が分からない
1. Wonoloを再び使う魅力を感じない

<work-media name="research_deck_01.png,research_deck_02.jpg,research_deck_03.jpg,research_deck_04.jpg,research_deck_05.jpg" />

## アイデアスケッチ

リサーチ結果を元にプロダクトのどの部分を改善するかの計画を、共同リーダーの<a href="https://www.linkedin.com/in/jsnwux/" target="_blank">Jason Wu</a>と共に立てました。そしてデザインスタジオと呼ばれる、チームで行うアイデアスケッチのワークショップを開きました。改善する項目ごとに複数人が同時にアイデアを考えてUIをスケッチし、お互いに良かったアイデアを取り入れながら3ラウンド繰り返しました。最終的に投票をすることで全員の意思でデザインの方向性を決めました。

<work-media name="design_studio.jpg" alt="デザインスタジオの様子" />

<work-media name="design_studio_badges.jpg,design_studio_profile.jpg,design_studio_rating.jpg,design_studio_home.jpg" />

## UIデザイン

このプロジェクトでは、Android、iPhone、Webの3つのプラットフォームのデザインをする必要がありました。Wonoloユーザーの多いAndroid版を最初に設計し、ユーザーテストを行いました。検証を繰り返し、最終的に決まったデザインをご紹介します。

## ナビゲーション

これまでのWonoloのアプリはドロワーメニューが採用されていました。しかし、プロフィール画面がどこにあるのか分かりづらく、Wonoloの課題であるプロフィール入力達成の妨げになっていました。そこで、タップしなくても各メニューを見ることのできるボトムナビゲーションに変更しました。

<work-media name="navigation_ja.png" alt="Wonoloのナビゲーション" caption="近年、デバイスが大きくなるに伴い、画面上部がタップし辛いことから、Androidでもボトムナビゲーションが利用されるケースが増えています。" />

## ユーザーに必要な情報をさまざまなカード形式で届ける

ホーム画面はクライアントの要望にはありませんでしたが、ユーザー調査で、ホーム画面を使わずにすぐに他のページへ移動するユーザーが多かった為、改善すべきだと考えました。これまでWonoloからのお知らせが並んでいたホーム画面を一新し、ユーザーがこれまでに得た収入や、働いた仕事の種類や、時間をグラフにして伝えたり、次に予定されている仕事のスケジュールを表示しました。

<work-media name="home_card.jpg" alt="ホーム画面に配置したさまざまなタイプのカード" />

### ダッシュボードへと一新したホーム画面

<work-media name="home.mp4" alt="ホーム画面のモックアップ" />

## バッジ獲得までの達成度を表示し、ゲーム的に仕事探しを楽しめる

ユーザーはいつ、どのようなバッジがもらえるのか良く分かっていませんでした。そこでまず、バッジにプログレスバーを設け、バッジを獲得するまでの条件を表示しました。次に、獲得後にどのような報酬がもらえるのかを伝えるモーダル画面を制作しました。

<work-media name="badges.jpg" alt="バッジのインストラクション" caption="ユーザーはタップすることで、バッジの詳細を確認することができます。また、この条件を達成できる仕事一覧への動線を設けています。" />

## プロフィールの入力完了まであとどれくらい？

プロフィールの入力状況をステップで表示しました。また、その下にバナーで入力して欲しい質問文を出すことで、次に何を答えたら良いのか、タップしなくても分かるようにしました。回答フォームでは、ユーザーがなるべく迷わないように例文を表示しています。

<work-media name="profile_onboarding.jpg" alt="プロフィールのOnboarding画面" />

## プロフィールはどのように表示される？不安を取り除くためのデザイン

プロフィール公開時のユーザーの不安を取り除くために確認画面を挟み、公開設定をオンにするとどのようなことが起きるのか、またそのメリットを出しました。公開設定がオンのときにだけプロフィールをシェアすることが可能です。

<work-media name="profile_privacy.mp4" />

### プレビュー画面との違い

プロフィール情報が、企業の採用担当者からどのように見えるのかを確認できるように、プレビュー画面も新たに設けました。採用担当者から見える画面には、ユーザーの最近の仕事も掲載されています。また、バッジの進捗状況はユーザーのための機能なので、企業からは見えないようにしました。

<work-media name="profile_preview_ja.jpg" alt="プロフィールのプレビュー画面" />

## 企業からユーザーへ賛辞を贈る

プロフィールをより魅力的なものにするために、当初私たちは、企業がユーザーに対してスターによる評価を入力すると同時に、レビューコメントを書き加えるように設計しました。しかし、企業は一日に何人もパートタイムの人を雇うため、一人ひとりにコメントを残すことはあまり現実的ではありませんでした。そこで代わりに、企業からユーザーに「時間を厳守する(Punctual）」「礼儀正しい(Polite)」「準備万端(Prepared)」といったその人への賛辞を選んで残すことができる仕様に変えました。

<work-media name="profile_rating.jpg" alt="ユーザーの評価" caption="スターによる数字的な評価だけではないので、ユーザーのモチベーションに繋がりやすく、企業がプロフィールを閲覧した際にもどのような人かの判断材料となります。" />

## 次の一歩

<work-media name="next_step.jpg" alt="Wonoloの利用イメージ" />

このプロジェクトは1ヶ月間で行われました。今回のスコープには入らなかったものの、いくつか次にやるべき課題が見つかりました。

- バッジの仕組みを整理する
  - ジョブカテゴリーと呼ばれる、特定の業種の仕事を回数をこなすごとにレベルアップするバッジがありますが、他のバッジとは働きが異なります。名前を変えたり、グラフィックを変えることによって区別をする必要がありそうです。
- カレンダー機能を追加する
  - 現在、仕事を探す際にはリストビューとマップビューが提供されていますが、カレンダー機能があれば、働ける日付から仕事を選ぶことができたり、仕事のスケジュール管理ができるようになります。
