<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h1 style = "color:blue; text-align:center">WORLD OF WORK SERVICES - COOP</h1>
<h3 style = "color:green">    <br>Working with employment opportunities in: </h3>
<h4 style = "color:magenta">   
    <br>Sales
    <br>Engineering (all disciplines)<br> Management (all categories) 
    <br>Construction Management 
    <br>Entry level employment
    <br>Merit advancement
<h3 style = "color:green">
    <br>Professional positions based upon experience and education
    <br>Self-employment by becoming a working COOP member </h3>
    </h4><h5 style = "color:brown">
    <br>CALL (520) 300-6340, nk@World-of-work-services-coop.com
    <br>Kay or Josh Harmon, 141 S. 6th Ave, Unit 42, Tucson, Az 85702 </h5>
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
a {
  color: #42b983;
}
</style>
