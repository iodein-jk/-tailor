<template>
  <div class="access">
    <h1>テーラードイ：アクセス（地図）案内</h1>
    <div class="map">
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1590.9219162121105!2d135.50989064312776!3d34.63815766028666!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6000dde97ee13501%3A0x471aea7336885a99!2z44OG44O844Op44O844OJ44Kk!5e0!3m2!1sja!2sjp!4v1703834412914!5m2!1sja!2sjp" width="600" height="350" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>
    <h2>お洋服ねっと　お仕立/お直し専門店</h2>
    <p>店主:土井 義弘
    <br>電話:090-3612-3119
    <br>メール:doiman0101@yahoo.co.jp
    <br>営業時間:AM10:00～PM7:00
    <br>定休日:日曜日/祝日</p>
  </div>
</template>

<style>

.access {
  min-height: 100vh;
  padding-top: 4em;
  padding-bottom: 4em;
}

h1 {
  margin-top: 2em;
}

h2,h3 {
  margin-top: 0.75em;
}

p {
  margin-top: 0.5em;
}

.map {
  margin-top: 1em;
  position: relative;
  width: 100%;
  height: 0;
  padding-top: 75%; /* 比率を4:3に固定 */
}

/* Google Mapのiframe */
.map iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
</style>
