<script>
export default {
  name: 'remote-css',
  props: {
    href: {
      type: String,
      required: true
    }
  },
  render (h) {
    return h('link', { attrs: { rel: 'stylesheet', href: this.href } });
  }
};
</script>
