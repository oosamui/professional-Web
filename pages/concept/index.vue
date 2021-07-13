<template>
  <layout-wrapper>
    <layout-visual
      title=""
      :height="40"
      visual="visual-concept"
    ></layout-visual>
    <div class="container w-full mx-auto pt-20 pb-20 px-6 md:px-0">
      <h3 class="text-2xl text-red-800 font-extrabold mb-5 text-center">
        打ち合わせやリモートワークができるちょっとした空間
      </h3>
      <div class="clearfix p-4 mb-10">
        <img
          src="@/assets/img/テーブル.jpg"
          class="float-right ml-4 my-2 h-56"
        />
        <div>
          <p class="mb-5">
            Mdn Cafe
            では、リモートワークや会社の打ち合わせなどが快適に行える空間を提供するカフェです。<br />
            リモートワークや打ち合わせを快適にするため全室個室にしています。<br />
            オンラインでの作業ができるようにWifi環境完備、週末は勉強会の場所としても提供しています。
          </p>
          <p class="mb-5">
            お食事は天然素材を使ったドーナツ・パンケーキを開発しています。<br />
            シンプルな素材と調理方法で食材本来の味を引き立てる自慢のドーナツ・パンケーキを提供しています。<br />
            コーヒーはブラジル産の豆を使用して、酸味とすっきりとした苦みがあるコーヒーになります。
          </p>
        </div>
      </div>
      <base-button name="トップへ戻る" link="/"></base-button>
    </div>
  </layout-wrapper>
</template>

<script>
export default {
  head() {
    return {
      title: 'コンセプト',
    }
  },
}
</script>
