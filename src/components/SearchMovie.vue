<template>
  <div class="search-movie">
    <div class="search">
      <v-text-field class="text-h1" placeholder="Введите название фильма..." variant="plain"></v-text-field>
      <span class="material-symbols-outlined" @click="console.log(2)">
        search
      </span>
    </div>
    <div class="select">
      <v-select :items="items" item-title="name" variant="plain"></v-select>
  </div>
</div>
    
</template>

<script>

export default {
data(){
  return {
    items: [
        { value: "title", name: "По названию" },
        { value: "year", name: "По году" },
        { value: "rating", name: "По рейтингу" },
        { value: "timing", name: "По длительности" }
      ],
  }
}
};
</script>

<style scoped>
.search-movie{
  margin-top: 120px;
  margin-left: 74px;
  width: 1000px;
  display: flex;
  
}
.search {
  padding: 10px;
  border-radius: 30px;
  height: 45px;
  width: 700px;
  background-color: #F3F7F8;
  border-radius: 30px;
  display: flex;
  justify-content: end;
  align-items: center;
  font-size: 36px;
}

.material-symbols-outlined {
  color: #BDC3C7;
  font-size: 36px;
  cursor: pointer;
}

.select {
  margin-left: 10px;
  padding-right: 0px;
  padding: 20px;
  height: 45px;
  width: 250px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #F3F7F8;
  border-radius: 30px;
}
</style>