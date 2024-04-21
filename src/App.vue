<template>
  <div class="container">
    <div class="row pt-3">
      <div class="col"></div>
      <div class="col-4">
        
      </div>
      <div class="col-3 my-auto">
        <form id="form">
          <h1 class="mb-4 text-center">社群網站登錄</h1>
          <input
            type="text"
            placeholder="請輸入會員名稱"
            class="mb-3 px-3 pe-4 py-2"
          />
          <input
            type="text"
            placeholder="請輸入電子郵件"
            class="mb-3 px-3 pe-4 py-2"
          />
          <input
            type="password"
            placeholder="請輸入密碼"
            class="mb-4 px-3 pe-4 py-2"
          />
          <button class="btn btn-lg btn-primary w-100" type="submit">
            註冊
          </button>
        </form>
      </div>
      <div class="col"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      message: 'Hello World',
    };
  },
};
</script>