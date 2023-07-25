<script>
export default {
  name: "hello",
  data() {
    return {
      msg: "Welcome to Vue.js App"
    };
  },
  render() {
    return (
      <h1>{ this.msg }</h1>
    );
  }
};
</script>

<style scoped>
h1 {
  color: darkgreen;
}
</style>
