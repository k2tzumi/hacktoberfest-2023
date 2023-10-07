---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
title: OSSへの感謝を伝える
# some information about the slides, markdown enabled
info: 日頃の感謝を伝えてみませんか？  
# persist drawings in exports and build
drawings:
  persist: false
# page transition
transition: slide-left
# use UnoCSS
css: unocss
fonts:
  # basically the text
  sans: 'Noto Sans JP'
  # use with `font-serif` css class from windicss
  serif: 'Noto Serif JP'
  # for code blocks, inline code, etc.
  mono: 'Noto Sans Mono'
addons:
  - "@katzumi/slidev-addon-qrcode"
  - "@katzumi/slidev-addon-blog-card"
  - "slidev-addon-components"
---

# OSSへの感謝を伝える

[蒲田温泉で前夜祭（PHPカンファレンス非公式）](https://connpass.com/event/296001/)　Oct 7th, 2023.  
v0.0.3

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/k2tzumi/clean-architecture-anti-pattern/blob/main/slides.md" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
layout: two-cols-header
---

# 自己紹介

katzumi（かつみ）と申します  

以下のアカウントで活動しています    

::left::

<img src="https://pbs.twimg.com/profile_images/799890486773170176/KN4gKfS2_400x400.jpg" class="rounded-full w-40 mt-16 mr-12　float-left"/>  
<QRCode width="180" height="180" value="https://twitter.com/katzchum" color="4329B9" image="Logo_of_X.svg" />

<simple-icons-x /> [katzchum](https://twitter.com/katzchum)

::right::

<img src="https://avatars.githubusercontent.com/u/1182787?v=4" class="rounded-full w-40 mt-16 mr-12"/>

<logos-github-octocat /> [k2tzumi](https://github.com/k2tzumi)  
<simple-icons-zenn /> [katzumi](https://zenn.dev/katzumi)  

<br />

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: two-cols-header
transition: fade-out
---


# お願い

写真撮影、SNSでの実況について

登壇者の励みになるので是非ともご意見やご感想など、フィードバック頂けると助かります mm  
あとでスライドを公開します

::left::

<Transform :scale="2.5">
　　　🙆‍♀📷<ph-projector-screen-chart-light /><br />
　　　🙅‍♂📹💸<br />
　　　🙅📸👨‍👦‍👦<br />
</Transform>

::right::

<Transform :scale="2">
<fa6-brands-square-x-twitter />
</Transform>
<br />
<a href="https://twitter.com/search?q=%23kamataonsen_zenyasai">#kamataonsen_zenyasai</a>

---
layout: fact
---

# 推してるOSS
# ありますか？

---
layout: center
---

# 祝200Stars🎉
<Tweet id="1705769690033979501"/>

---
layout: center
---

# 良いインスピレーションを貰いました！

<Tweet id="1705594010335842604"/>

---
layout: fact
---

# お世話になっているOSSに感謝を伝えたい！

---
layout: image-right
image: https://img.freepik.com/free-vector/delicious-mug-of-beer-with-foam-oktoberfest_52683-43030.jpg?w=1380&t=st=1696331613~exp=1696332213~hmac=ce49d0d867e15133ce1b1d9513bcd0d8c52fabb7b77358ce9a6a46bdeb0d0732
---

# [Hacktoberfest2023](https://hacktoberfest.com/)

絶賛開催中！！

<Tweet id="1707954447505379544"/>


---
layout: default
---

# What's Hacktoberfest?
GPTさん曰く

<blockquote>
<p>このイベントはオクトーバーフェストにかけています。</p>
<p>Hacktoberfestという名前は、October（10月）とHack（プログラミングの俗語）を合わせた造語です。</p>
<p>オクトーバーフェストはドイツのミュンヘンで開催される世界最大のビール祭りで、10月に行われます。</p>
<p>Hacktoberfestは、オープンソースのプロジェクトに貢献することで、</p>
<p>ビールではなくTシャツやバッジなどのデジタルな報酬を得られるイベントです。</p>
<p>Hacktoberfestの趣旨は、オープンソースのコミュニティを支援し、スキルを磨き、新しい人とつながることです。</p>
<p>Hacktoberfestは2023年で10周年を迎え、これまでに数千人の開発者が参加しています。</p>
</blockquote>

---
layout: fact
---

# 今なら何と！

---

# 色々貰えちゃいます！
去年の報酬

<Tweet id="1622538122671321088"/>

---
layout: fact
---

# 悲報 😭

---

# SDGs
時代の流れか。。

https://hacktoberfest.com/about/#digital-rewards
<blockquote>
<p>In its tenth year, we’re making important changes to Hacktoberfest to help ensure its sustainability for the next decade.</p>
<p>Most notably, we will be moving away from the t-shirt rewards we have previously provided to a digital reward kit.
</p>
</blockquote>

今年で10年目を迎えるハクトーバーフェストですが、次の10年も継続できるよう、重要な変更を行います。  
最も注目すべき点は、これまで提供してきたTシャツのリワードから、デジタルリワードキットへと移行することです。

<!--
国によっては関税等を負担する必要があったり問題になっていたようです。
-->

---

# 超ざっくり説明

* 申し込み（アカウント登録）する
* 10月1日から10月31日までの間に、GitHubまたはGitLab上のHacktoberfestに参加表明しているリポジトリに4つ以上のプルリクエストを送る
* 参加者は、先着で自分の名前で木を植えてもらうか、Hacktoberfest2023のデジタルリワードキットをもらうことができる

---

# 申し込み方法

[START HACKING](https://hacktoberfest.com/auth/) から！

エントリーの仕方は記事にしました！

https://zenn.dev/katzumi/articles/hacktoberfest-2023#%E7%94%B3%E3%81%97%E8%BE%BC%E3%81%BF%E6%89%8B%E9%A0%86


<QRCode width="180" height="180" value="https://zenn.dev/katzumi/articles/hacktoberfest-2023#%E7%94%B3%E3%81%97%E8%BE%BC%E3%81%BF%E6%89%8B%E9%A0%86" color="4329B9" image="zenn-dev.svg" />

---

# 注意点

* 公開リポジトリ且つhacktoberfestのトピックがついている必要あり
若しくはPull Requestに `hacktoberfest-accepted` ラベルを付けてMergeしてもらう必要があります
* 自身のOSSにセルフ貢献してもOKです

詳細は記事の方で！

https://zenn.dev/katzumi/articles/hacktoberfest-2023#%E3%82%88%E3%81%8F%E3%81%82%E3%82%8B%E8%B3%AA%E5%95%8F

<QRCode width="180" height="180" value="https://zenn.dev/katzumi/articles/hacktoberfest-2023#%E3%82%88%E3%81%8F%E3%81%82%E3%82%8B%E8%B3%AA%E5%95%8F" color="4329B9" image="zenn-dev.svg" />


---

# 対象リポジトリ
PHPerはここから！

https://github.com/topics/hacktoberfest?l=php

<QRCode width="180" height="180" value="https://github.com/topics/hacktoberfest?l=php" color="4329B9" image="github-mark.svg" />

---

# プルリクエストを送るのは難しいという方へ
スポンサーになるという方法もあるけれど。。

![GitHub Stars](https://stars.github.com/card.jpg)

---
layout: two-cols-header
---

# ノミネートしてみませんか？
推薦制度になります

::left::

ここから！  
https://stars.github.com/nominate/

<QRCode width="180" height="180" value="https://stars.github.com/nominate/" color="4329B9" image="github-mark.svg" />

::right::

JP勢は matz さん含め4名  
https://stars.github.com/profiles/?country=Japan

<QRCode width="180" height="180" value="https://stars.github.com/profiles/?country=Japan" color="4329B9" image="github-mark.svg" />

---

# 最後に

イベント記事を上げる際は、ちゃんと差分を確認しましょう！  


---
layout: fact
---

# 良いOSSライフを！


---
layout: end
---

ご清聴ありがとうございました
