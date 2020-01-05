<template>
  <div>
    <h1>Welcome to bootstrap vue app</h1>
    <div class="cont">
  <b-tabs content-class="mt-3">
    <b-tab title="First" active>
      <div>
  <b-button>Button</b-button>
  <b-button variant="danger">Button</b-button>
  <b-button variant="success">Button</b-button>
  <b-button variant="outline-primary">Button</b-button>
</div>
<br><br>
<div>
  <b-form inline>
    <label class="sr-only" for="inline-form-input-name">Name</label>
    <b-input
      id="inline-form-input-name"
      class="mb-2 mr-sm-2 mb-sm-0"
      placeholder="Jane Doe"
    ></b-input>

    <label class="sr-only" for="inline-form-input-username">Username</label>
    <b-input-group prepend="@" class="mb-2 mr-sm-2 mb-sm-0">
      <b-input id="inline-form-input-username" placeholder="Username"></b-input>
    </b-input-group>

    <b-form-checkbox class="mb-2 mr-sm-2 mb-sm-0">Remember me</b-form-checkbox>

    <b-button variant="primary">Save</b-button>
  </b-form>
</div>
    </b-tab>
    <b-tab title="Second"><p>I'm the second tab</p></b-tab>
    <b-tab title="Disabled" disabled><p>I'm a disabled tab!</p></b-tab>
  </b-tabs>
</div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
.cont{
  margin-top: 3%;
}
a {
  color: #42b983;
}
</style>
