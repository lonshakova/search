<template>
  <div class="search-movie">
    <v-text-field class="search" variant="regular"><span class="material-symbols-outlined">
        search
      </span></v-text-field>
  </div>
</template>

<script>

export default {

};
</script>

<style>
.search-movie {
  margin-top: 120px;
  margin-left: 74px;
  border-radius: 30px;
}

.search {
  height: 65px;
  width: 640px;
  background-color: #F3F7F8;
  border-radius: 30px;
  display: flex;
  justify-content: end;
}

.material-symbols-outlined {
  color: #BDC3C7;
  font-size: 36px;
}
</style>