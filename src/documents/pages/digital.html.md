```
title: Digital
layout: page
pageOrder: 1

```


<!-- <div class="row-fluid"> -->
	<!-- <div class="span12"> -->
	<div id="Carousel" class="carousel slide">
		<ol class="carousel-indicators">
			<li data-target="#Carousel" data-slide-to="0" class="active"></li>
			<li data-target="#Carousel" data-slide-to="1"></li>
			<li data-target="#Carousel" data-slide-to="2"></li>
			<li data-target="#Carousel" data-slide-to="3"></li>
			<li data-target="#Carousel" data-slide-to="4"></li>
		</ol>
		<div class="carousel-inner">
			<div class="item active">
				<img src="https://pp.vk.me/c315227/v315227109/a80c/bwSleRb1mcI.jpg" width="100%">
				<div class="carousel-caption">
					<h4>Plein air</h4>
					<p>Открыть новые грани своей личности.</p>
				</div>
			</div>
			<div class="item">
				<img src="http://pcdn.500px.net/8336689/b8524f7f1c02c45bfd160bcfc4e5eceb3e5dc078/5.jpg" width="100%">
				<div class="carousel-caption">
					<h4>Wedding</h4>
					<p>Запечатлить первый шаг вашей новой жизни.</p>
				</div>
			</div>
			<!--div class="item">
				<img src="https://pp.vk.me/c417619/v417619109/6b06/OlPkmQgjak4.jpg" width="100%">
				<div class="carousel-caption">
					<h4>Fashion</h4>
					<p>Открыть себя в глянце.</p>
				</div>
			</div-->
			<!--div class="item">
				<img src="http://pcdn.500px.net/41197394/3221b4a2f5171ad119941d6579ef5550f639c8ca/2048.jpg" width="100%">
				<div class="carousel-caption">
					<h4>Портрет</h4>
					<p>Запечатлить хорошее настроение.</p>
				</div>
			</div-->
			<div class="item">
				<img src="https://pp.vk.me/c405228/v405228658/b9dc/50mS49WIlM4.jpg" width="100%">
				<div class="carousel-caption">
					<h4>Beauty</h4>
					<p>Остановить время.</p>
				</div>
			</div>
		</div>
		<a class="left carousel-control" href="#Carousel" data-slide="prev">‹</a>
		<a class="right carousel-control" href="#Carousel" data-slide="next">›</a>
	</div>
	<!-- </div> -->
	<div class="row-fluid">
        <div class="span3">
          <h2>Fashion</h2>
           <p>Модельная фотосъёмка для создания модельного, актерского портфолио, а также детское модельное фото.</p>
          <p><a class="btn" href="/posts/fashion">Смотреть &raquo;</a></p>
        </div>
        <div class="span3">
          <h2>Portrait</h2>
           <p>Портрет это в первую очередь индивидуальностью На портрете изображается внешний облик (а через него и внутренний мир) конкретного, реального, существующего в настоящем человека. </p>
          <p><a class="btn" href="/posts/portrait">Смотреть &raquo;</a></p>
       </div>
        <div class="span3">
          <h2>Beauty</h2>
          <p>Много макияжа, внешняя красота и глянец.</p>
          <p><a class="btn" href="/posts/beauty">Смотреть &raquo;</a></p>
        </div>
         <div class="span3">
          <h2>Wedding</h2>
          <p>Профессиональная свадебная фотосъемка.</p>
          <p><a class="btn" href="/posts/wedding">Смотреть &raquo;</a></p>
        </div>
      </div>
  	
<!--/div-->
<!--%- @getBlock("scripts").add(["/vendor/twitter-bootstrap/js/bootstrap-carousel.js"]).toHTML() %-->

<!--nav class="linklist">
	<% for document in @getCollection('posts').toJSON(): %>
		<li> 
		<a href="<%= document.url %>"><%= document.title %></a></li>
	<% end %>
</nav-->
