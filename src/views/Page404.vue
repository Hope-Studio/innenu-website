<template>
  <div class="container">
    <h1 mt-1>未找到界面</h1>
    <p>
      很抱歉，您打开的网页不存在。这可能是由于您输入了错误的路径，或者网页尚未制作。
    </p>
    <p>同时，这也可能是一个bug。</p>
    <p>
      您可以将此错误反馈给
      <RouterLink
        to="http://wpa.qq.com/msgrd?v=3&amp;uin=1178522294&amp;site=qq&amp;menu=yes"
        >Mr.Hope</RouterLink
      >
    </p>
    <h1 mt-1>Page not found</h1>
    <p>
      We are sorry. The page you are looking for does not exist. This can be
      caused by inputing the wrong url, or the website is not made yet.
    </p>
    <p>Also, this can be a bug.</p>
    <p>
      You can report this error to
      <RouterLink
        to="http://wpa.qq.com/msgrd?v=3&amp;uin=1178522294&amp;site=qq&amp;menu=yes"
        >Mr.Hope</RouterLink
      >.
    </p>
  </div>
</template>
<script lang="ts">
export default {
  name: "Page404",
};
</script>
