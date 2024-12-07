<style>
    @font-face {
    font-family: 'CaskaydiaCove';
    src: url('../fonts/CaskaydiaCove.woff2') format('woff2');
  }
@font-face {
  font-family: 'HarmonyOSSans';
  src: url('../fonts/HarmonyOSSans.woff2') format('woff2');
}
:root {
    --dark-background-color: #424242;
    --light-background-color: #fff;
    --shadow: 0px 10px 20px rgba(0, 0, 0, 0.04), 0px 2px 6px rgba(0, 0, 0, 0.04), 0px 0px 1px rgba(0, 0, 0, 0.04);
    --avatar-size: 100px;
    --emoji-size: 36px;
}
.title-box {
    display: flex;
    flex-direction: column;
    flex-grow: 1;
    align-content: center;
    justify-content: center;
    padding: 0;
    .element {
        margin: 2px auto;
        /* background-color: var(--card-background); */
        /* box-shadow: var(--shadow-l2); */
        /* border-radius: 50%; */
    }
}
.avatar {
    position: relative;
    width: var(--avatar-size);
    height: var(--avatar-size);
    margin: 0;
    flex-shrink: 0;
}
.avatar .profile {
    border-radius: 50%;
    box-shadow: var(--shadow);
    width: var(--avatar-size);
    height: var(--avatar-size);
    border-radius: 50%;
}
@media (prefers-color-scheme: light) {
    .avatar .emoji {
        border-radius: 100%;
        position: absolute;
        font-size: 20px;
        width: var(--emoji-size);
        height: var(--emoji-size);
        line-height: var(--emoji-size);
        bottom: 0px;
        right: 0px;
        text-align: center;
        background-color: var(--light-background-color);
        box-shadow: var(--shadow);
    }
}
@media (prefers-color-scheme: dark) {
    .avatar .emoji {
        border-radius: 100%;
        position: absolute;
        font-size: 20px;
        width: var(--emoji-size);
        height: var(--emoji-size);
        line-height: var(--emoji-size);
        bottom: 0px;
        right: 0px;
        text-align: center;
        background-color: var(--dark-background-color);
        box-shadow: var(--shadow);
    }
}
.gallery-box {
    display: flex;
    flex-grow: 1;
    max-width: 90vw;
    overflow-x: auto;
    white-space: nowrap;
    padding: 8px;
    .element {
        flex: 0 0 auto;
        margin-right: 16px;
    }
}
body {
    font-family: HarmonyOSSans,CaskaydiaCove,sans-serif;
}
</style>

<div class="title-box">
  <div class="element avatar">
    <img src="assets/svg/dvdbr3o.svg" width="100px" class="profile" />
    <div class="element emoji"> 🥰 </div>
  </div>
  <h1 class="element">DvdBr3o</h1>
  <h4 class="element">一个天天想她的白痴</h4>
</div>

---

<h2> ⚒️ 技术栈 </h2>

- 啥也不会

- 会点 `C++`

<h2> ✅ 正在做 </h2>

- 基于 `C++20` template / `Vulkan` 的 modern GUI 框架

- 借鉴 `coffeescript` 并兼容 `lua` 的面向配置的脚本语言

- 基于前两者的音乐宿主 DAW

~~(以上永远不会实现)~~

<h2> ❤️ 喜欢 </h2>

- 💻 学点 `C++`

- 🎶 一点点电子音乐 ⊇ {(Botanica, Hyper, Riddim, Kawaii, Pop)}

- 🖼️ 一点点 art

- 🕹️ COD ~~(买不起本体所以特指 Warzone 😅)~~

- 💌 她
  
<h2> 🔗 更多の我 </h2>

[![](partials/cardlinks/blog.svg)](https://blog.dvdbr3o.top/)

[![](partials/cardlinks/zhihu.svg)](https://www.zhihu.com/people/davidbro)

[![](partials/cardlinks/mastodon.svg)](https://mastodon.social/@dvdbr3o)

[![](partials/cardlinks/bilibili.svg)](https://space.bilibili.com/357237146)
