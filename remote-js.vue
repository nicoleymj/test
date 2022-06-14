<script>
export default {
  name: 'remote-css',
  props: {
    src: {
      type: String,
      required: true
    }
  },
  render (h) {
    return h("script", { attrs: { type: "text/javascript", src: this.src } });
  }
};
</script>
