<template>
<div>
  <ul>
    <li class="item1">Music</li>
    <li class="item2">Video</li>
  </ul>
  <h2>The Thumping Tommys</h2> 
  <ul>
    <li class="item1">Shows</li>
    <li class="item2">Contact</li>
  </ul>
</div>
</template>

<script>
export default {

}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
div {
  display: flex;
  background-color: antiquewhite;
}
ul {
  display: flex;
  justify-content: center;
  align-items: center;
  list-style: none;
  margin: auto;
  padding: 0;
}
.item1 {
  margin-right: .5rem;
  padding: .5rem;
}
.item2 {
  margin-left: .5rem;
  padding: .5rem;
}
li:hover {
  background-color: rgba(0,0,0,0.1);
  border-radius: 4px;
}
</style>
