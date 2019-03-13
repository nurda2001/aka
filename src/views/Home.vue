<template>
 <div class="container">
 	<div class="uk-child-width-1-2@s uk-grid-match" uk-grid>
 		<div>
 	<h1>Добро пожаловать</h1>
 	<h2>Сайт был написан <strong><a href="https://vk.com/akmolya">Акмолдир</a></strong></h2>
 	<h3>Для просмотра надо будет зарегистрироваться</h3></div>
 <div>
 	</div></div>
 	<div class="uk-child-width-1-1@s uk-grid-match" uk-grid>
 	<div>
 	<v-carousel hide-delimiters>
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
    ></v-carousel-item>
  </v-carousel>
</div>
</div>
</div>
 </div></template>

<script>
	export default {
    data () {
      return {
        items: [
          {
            src: 'https://www.pixelstalk.net/wp-content/uploads/2016/05/Black-Music-HD-Wallpapers.png'
          },
          {
            src: 'https://wallpapercave.com/wp/0l0kzYB.jpg'
          },
          {
            src: 'https://i.pinimg.com/originals/36/f4/e6/36f4e648dfb9003602251bd93cd76722.jpg'
          },
          {
            src: 'https://i.pinimg.com/originals/55/fd/38/55fd3816e8dde9d7ade143517263147c.jpg'
          }
        ]
      }
    }
  }
  </script>
