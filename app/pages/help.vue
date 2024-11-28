<template>
  <div>
    <div class="w-full">
      <CommonHeader>
        帮助
      </CommonHeader>

      <InstallPwa />

      <div class="mx-auto max-w-md w-full rounded-2xl p-2" text-left>
        <FAQItem title="什么是模式？">
          <ul>
            <li><b>模糊匹配</b>：展示所有含当前选中任意食材的菜谱</li>
            <li><b>精准匹配</b>：展示所有含当前选中所有食材的菜谱</li>
            <li><b>生存模式</b>：展示当前选中食材即可制作的所有菜谱</li>
          </ul>
        </FAQItem>

        <FAQItem title="如何快速清空所选食材和工具?">
          <div inline-flex items-center justify-center>
            点击顶部 <div i-mdi-pot-steam-outline mx-1 inline-block /> 图标即可。
          </div>
        </FAQItem>

        <hr h="1" my="4" bg-black>
      </div>
    </div>
    <BaseFooter mt-4 />
  </div>
</template>
