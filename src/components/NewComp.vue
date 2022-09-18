<template>
  <div>
    <button class="new-button">New Button</button>
  </div>
</template>

<script>
export default {
  name: "NewComp",
};
</script>

<style>
.new-button {
  padding: 15px 20px;
  border: none;
  background-color: blueviolet;
  color: white;
  border-radius: 5px;
  font-size: 15px;
  font-weight: 200;
  transition: 0.4s;
}

.new-button:hover {
  box-shadow: 0px 5px 15px 1px rgba(0, 0, 0, 0.2);
}
</style>