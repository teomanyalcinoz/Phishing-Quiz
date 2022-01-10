<template>
  <main>
    <div class="dd">
      <div class="p-40 ml-20">
        <h3 class="font-bold text-4xl text-white">Kimlik Avı</h3>
        <div class="text-2xl text-white">
          Kimlik Avı saldırıları, yaygın sosyal mühendislik saldırılarındandır.
          Sosyal mühendislikte kimlik avı saldırı vektörleri bir telefon
          görüşmesi, bir metin mesajı veya bir e-posta olabilir. Tahmin etmiş
          olmanız gerektiği gibi, bu quizde odak noktamız saldırı vektörü olarak
          e-postalar.
        </div>
        <v-btn class="top-20" x-large rounded color="primary"
          >QUIZE BASLAYALIM</v-btn
        >
      </div>
      <div id="ddd">
        <v-img height="100%" src="../assets/ph.gif"></v-img>
      </div>
    </div>
  </main>
</template>

<style scoped>
.dd {
  background-color: cornflowerblue;
}
#ddd {
  margin-top: -215px;
  margin-left: 900px;
  height: 400px;
  width: 400px;
}
main {
  background-color: #92a8d1;
}
</style>


<script>
export default {
  name: "Home",
};
</script>
