<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style>
    /************************************************************
  ** 请将全局样式拷贝到项目的全局 CSS 文件或者当前页面的顶部 **
  ** 否则页面将无法正常显示                                  **
  ************************************************************/

  html {
    font-size: 16px;
  }

  body {
    margin: 0;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen', 'Ubuntu', 'Cantarell', 'Fira Sans',
      'Droid Sans', 'Helvetica Neue', 'Microsoft Yahei', sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }

  body * {
    box-sizing: border-box;
    flex-shrink: 0;
  }

  #app {
    width: 100vw;
    height: 100vh;
  }

  .flex-row {
    display: flex;
    flex-direction: row;
  }

  .flex-col {
    display: flex;
    flex-direction: column;
  }

  .justify-start {
    justify-content: flex-start;
  }

  .justify-center {
    justify-content: center;
  }

  .justify-end {
    justify-content: flex-end;
  }

  .justify-evenly {
    justify-content: space-evenly;
  }

  .justify-around {
    justify-content: space-around;
  }

  .justify-between {
    justify-content: space-between;
  }

  .items-start {
    align-items: flex-start;
  }

  .items-center {
    align-items: center;
  }

  .items-end {
    align-items: flex-end;
  }

  .van-cell input {
    flex-shrink: unset;
  }

  .cf_sidebar_wrapper {
    display: flex;
    flex-direction: row;
    height: 100%;
  }

  .cf_sidebar_content_wrapper {
    flex: 1;
  }
</style>