<script setup>
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
    <template #heading>Who is he?</template>

    Masamichi Kanakuboは日本在住のソフトウェアエンジニアです.
    <ul>
      <li>年齢: 19歳(2004年生まれ)</li>
      <li>拠点: 滋賀, 大阪</li>
      <li>学歴: 立命館大学 情報理工学部 情報理工学科 (在学)</li>
      <li>ポジション: カスタマーエンジニア@
        <a href="https://plaid.co.jp/">Plaid, inc</a>
      </li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tech Stack</template>

    Masamichi Kanakuboはフルスタックエンジニアです. 彼は以下の技術のプロフェッショナルです.
    <br />
    バックエンド
    <ul>
      <li>Python</li>: Django, FastAPI
    </ul>
    フロントエンド
    <ul>
      <li>JavaScript, TypeScript</li>: Vue3
    </ul>
    詳細な技術スタックは,
    <a href="https://github.com/MasamichiKanakubo">こちら</a>
    から確認できます.
     <br />

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading> Product</template>
    <ul>
      <li>選曲アプリ「
        <a href="https://mood-hub-watnow.vercel.app/">MoodHub</a>
        」</li>Stack: FastAPI, Next.js, Three.js, Chakra UI, Firebase, MongoDB
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>

    Masamichi Kanakuboは
    <a href="https://twitter.com/watnows">関西学生IT団体watnow</a>
    に所属しています.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contact</template>
    お仕事のご依頼やご相談は次の連絡先までお願いします.
    <ul>
      <li>大学: 
        <a href='is0719sf@ed.ritsumei.ac.jp'>is0719sf@ed.ritsumei.ac.jp</a>
      </li>
      <li>個人:
        <a href="renlijinjiubao808@gmail.com">renlijinjiubao808@gmail.com</a>
      </li>
      <li>Twitter:
        <a href="https://twitter.com/ma_kanakubo">@ma_kanakubo</a>
      </li>
    </ul>
  </WelcomeItem>
</template>
