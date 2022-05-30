<template>
  <div class="body">
    <div class="head">
      <h1>わたしについて</h1>
    </div>
    <div class="profile">
      <div class="leftPro">
        <ul>
          <li>Name : chisato takahashi</li>
          <li>Age : 22</li>
          <li>Born : 1999.8.18</li>
          <li>Blood type : A</li>
          <li>Height : 175.6cm</li>
          <li>Hometown : chiba(kamagaya)</li>
        </ul>
      </div>
      <div class="rightPro">
        <img src="@/assets/chisamikan.jpg" alt="" class="photo" />
      </div>
    </div>
    <hr />
    <div class="historyList">
      <ul>
        <div class="top">history</div>
        <li>1999.08 長崎で誕生 その後千葉へ</li>
        <li>2005.06 人見知りで幼稚園ではずっと絵を描いて過ごす</li>
        <li>
          2010.03 友達に誘われバスケ部に入部 自分は運動ができないのだと気づく
        </li>
        <li>
          2012.04 中学では吹奏楽部へ入部
          "サックス吹いてそうな顔"という理由で楽器が決まる
        </li>
        <li>2013.03 サックス五重奏でアンサンブルコンテスト金賞を獲得</li>
        <li>2015.04 吹奏楽部が強い千葉県立松戸六実高等学校へ入学</li>
        <li>2015.05 演劇部の新歓公演で魅了され演劇部へ入部</li>
        <li>
          2015.10 初舞台、終わった後の拍手が気持ちよすぎて演劇にさらにハマる
        </li>
        <li>2017.08 法政大学のオープンキャンパスに参加し、大学受験を決意</li>
        <li>2018.03 受験した全ての大学が落ち、絶望する</li>
        <li>2018.04 柏の河合塾で浪人生活を始める</li>
        <li>2019.04 法政大学経営学部経営戦略学科へ入学</li>
      </ul>
    </div>
    <hr />
    <div class="top2">my profile</div>
    <div class="my-about">
      <div>
        <img src="@/assets/papoko.jpeg" alt="" class="photo2" />
      </div>
      <div class="message">
        <p>
          千葉県鎌ケ谷市在住、しし座のA型。何型っぽい？と周りに聞くと大体O型と言われる大雑把な性格。<br />
          好きなセリフは、
        </p>
        <h4>
          "人間はね、できると思ったら何だって出来るんでだって!!<br />100点とるにはまず出来るって100%思い込める精神トレーニングが必要なんだって!!"
        </h4>
        <p>
          浪人生の時、センセイ君主に出てくるパピコさんのセリフのおかげでスーパーポジティブガールでした！<br />
          楽しいことがとにかく大好き。死ぬまでにやりたいことは鳥取砂丘の砂とエジプトの砂を比較すること。<br />
          これを言った時に、しょうもな！！やろう！！って言ってくれる友達が大好きです(笑)
        </p>
      </div>
    </div>
    <hr />
    <div class="top3">my favorite music</div>
    <div class="music">
      <ul>
        <div class="message2">
          youtubeで新しい音楽を探すのがお宝探しみたいですきです。ライブ映像やMVを見るとその曲の背景がより鮮明になるのもすきです。<br />
          いつかライブに行きたいと思ってたバンドが去年解散しました。それからは行きたいと思ったら会いに行くようにしてます。<br />
          音楽をみんなに布教するのもすきです。その曲を聴いた時に私のことを少しでも思い出せばいいというメンヘラ思考です(笑)
        </div>
        <li class="title">♪ アーケード/カネコアヤノ</li>
        <li>
          「仕事も真面目に行かないし、誰かの言うこと聞きたくない、すべてのことに理由がほしい」
        </li>
        <li class="title">♪ 少年の詩/THE BLUE HEART</li>
        <li>「どうにもならない事なんて、どうにでもなっていい事」</li>
        <li class="title">♪ オンリーワンダー/フレデリック</li>
        <li>「みんな違って、みんな優勝」</li>
        <li class="title">♪ 百八円の恋/クリープハイプ</li>
        <li>
          「終わったのは始まったから、負けたのは戦ってたから、別れたのは出会えたから」
        </li>
        <li class="title">♪ キルミー/SUNNY CAR WASH</li>
        <li>
          「ねぇキルミーベイベー殺してくれ 溢れるほどの愛で溺れさせてくれ」
        </li>
        <li class="title">♪ オシャレ大作戦/ネクライトーキー</li>
        <li>
          「涙が出たって大人なら誰にも見せないで終わらせないと、そうやって嘘もつくちょっとオシャレでしょ?」
        </li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
hr {
  margin: 0px 100px;
}
.head {
  display: flex;
  align-items: center;
  justify-content: center;
  border: 6px solid #000;
  height: 100px;
  margin: 0px 100px;
  padding: 40px;
}
.head h1 {
  font-size: 40px;
  letter-spacing: 30px;
}
.profile {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 120px 0px;
}
.leftPro {
  margin-right: 170px;
}

.leftPro ul {
  list-style: none;
  letter-spacing: 5px;
  line-height: 55px;
}
.photo {
  height: 500px;
}
.historyList {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 120px 0px;
}
.historyList li {
  line-height: 40px;
  font-size: 13px;
}
.top {
  border: 1px solid #000;
  padding: 7px 40px;
  margin-bottom: 24px;
}
.top2 {
  border: 1px solid #000;
  padding: 7px 40px;
  margin: 120px auto 50px auto;
  width: 440px;
}
.top3 {
  border: 1px solid #000;
  padding: 7px 40px;
  margin: 120px auto 20px auto;
  width: 440px;
}
.my-about {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 120px;
}
.photo2 {
  width: 350px;
}
.message p {
  font-size: 12px;
  width: 700px;
  letter-spacing: 2px;
  line-height: 38px;
}
.message h4 {
  letter-spacing: 1px;
  line-height: 40px;
}
.message {
  margin-left: 120px;
}
.music {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 120px;
}
.music ul {
  list-style: none;
}
.message2 {
  font-size: 13px;
  line-height: 40px;
  margin-bottom: 70px;
}
.title {
  font-weight: bold;
  text-align: center;
  margin-top: 40px;
}
.music li {
  font-size: 15px;
  line-height: 40px;
  text-align: center;
}
</style>
