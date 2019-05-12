<template>
  <div>
    <h1>{{ msg }}</h1>
    <counter />
    <item-list/>
  </div>
</template>

<script>
import Counter from "./Counter.vue";
export default {
  name: "HelloWorld",
  props: {
    msg: String
  },
  components: {
    Counter,
  }
};
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->

