<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>お問い合わせ</template>
    電話:090-3612-3119
    <br>メール:doiman0101@yahoo.co.jp
    <br>営業時間:AM10:00～PM7:00
    <br>定休日:日曜日/祝日
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>私たちの店舗について</template>
    店舗の所在地、営業時間、連絡先などを掲載しています。私たちの店舗に来て、あなたの完璧なスーツを作り上げるプロセスを体験してください。
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>あなたの完璧なスーツを作り上げるプロセス</template>
    オーダースーツの注文から完成までの流れを詳しく説明します。来店予約、カウンセリング、生地・スタイルの選択、採寸・試着、カスタマイズなどのステップを通じて、あなたの完璧なスーツを作り上げます。
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>あなたのスーツを長持ちさせるためのアフターケア</template>
    私たちは、オーダースーツのアフターケアについて説明します。例えば、1年間の無料修理サービスなど、あなたのスーツが長持ちするようにサポートします。アフターケアについてのご質問がございましたら、お気軽にお問い合わせください。
  </WelcomeItem>
</template>
