<template>
  <div class="main-footer">
    <div class="copyright">
      <div class="content flex-column">
        <div class="mian-footer-content">
          <span>Copyright © 2021-2022</span>
          <a href="https://www.bugdr.cn" target="_blank">个人网站</a>
          <a href="https://github.com/dpy0912/neteasecloudmusic" target="_blank"
            >项目地址</a
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainFooter',
  data() {
    return {

    }
  },
  components: {

  },
  mounted() {

  },
  methods: {

  }
}
</script>

<style lang="less" scoped>
.main-footer {
  align-items: center;
  width: 100%;
  background: @header-background-color;
  .copyright {
    padding: 1.2rem 0;
    text-align: center;
    .content {
      padding: 0;
      color: @blue;
      font-size: 1.2rem;
      .mian-footer-content {
        margin: 0 auto;
        width: 100%;
        a {
          color: @color-dark;
          margin-left: 5px;
          transition: color 0.15s ease-in-out,
            background-color 0.15s ease-in-out, border-color 0.15s ease-in-out,
            box-shadow 0.15s ease-in-out;
          &:hover {
            color: @color-theme;
          }
        }
      }
    }
  }
}
</style>
