<script setup></script>
<template>
  <p>safariでdisplay:none;が利かないのか確かめます</p>
  <label>
    <input class="notWrap" type="radio" />
    notWrap
  </label>
  <label>
    <input class="" type="radio" />
    notNone
  </label>

  <label>
    <span class="span">
      <input class="wrap" type="radio" />
      spanNone
    </span>
  </label>
  <label>
    <span class="">
      <input class="" type="radio" />
      spanNotNone
    </span>
  </label>
</template>
<style>
* {
  text-align: center;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  margin-top: 10px;
}

label,
input {
  cursor: pointer;
}

.notWrap {
  display: none;
}

.span {
  display: none;
}
</style>
