<template>
  <layout-wrapper>
    <layout-visual
      title="Information"
      :height="40"
      visual="visual-information"
    ></layout-visual>
    <div class="w-full md:max-w-3xl mx-auto pt-20">
      <h2 class="text-xl pb-5 border-b border-gray-500 border-solid font-bold">
        お知らせタイトル
      </h2>
      <div class="pt-4 mb-4">
        <time class="text-gray-700 text-base">2020.8.25</time>
      </div>
      <div class="mb-20">
        <h3>見出しが入ります・・・・・・</h3>
        <p>
          テキストが入りますテキストが入りますテキストが入りますテキストが入ります
        </p>
        <ul>
          <li>リスト・・・・・</li>
          <li>リスト・・・・・</li>
          <li>リスト・・・・・</li>
        </ul>
      </div>
      <base-button name="お知らせへ戻る" link="/information/"></base-button>
    </div>
  </layout-wrapper>
</template>

<script>
export default {
  head() {
    return {
      title: 'お知らせ詳細タイトル',
    }
  },
}
</script>
