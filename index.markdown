---
title: Roosje Pertz
layout: default
bio_title: Bio van een straffe madam
bio_description: In 2018 besliste Roosje Pertz om eens op een podium te zeggen wat
  ze dacht. Dat bleek pure comedy te zijn. Roosje Pertz is een grappige vrouw. Dat
  zeggen haar vrienden al lang.  Haar rake observaties vallen in de smaak bij een
  breed publiek. Goedgezind en flink, maar niet té braaf. Roosje gidst je met haar
  aparte blik langs de geijkte paadjes van de middenklasse. <br><br> In 2019 nam Michael
  Van Peel Roosje mee op tournee als een van zijn Young Ones. <br><br> Ze is ook te
  beluisteren op de podcasts Dertigerspraat en KiloCast. Met een Leuvens accent. Ooit
  wordt dat weer hip.  Roosje is heel sociaal op Twitter, Youtube, Facebook en Instagram.
bio_button: Luister naar mijn podcast!
socials_instagram_title: Roosje op Instagram
socials_twitter_title: Roosje op Twitter
socials_twitter_previous: Vorige
socials_twitter_next: Volgende
podcast_title: Dertigerspraat/Kilocast
copywriting_title: Copywriting
copywriting_text: In 2018 besliste Roosje Pertz om eens op een podium te zeggen wat ze dacht. Dat bleek pure comedy te zijn. Roosje Pertz is een grappige vrouw. Dat zeggen haar vrienden al lang.  Haar rake observaties vallen in de smaak bij een breed publiek. Goedgezind en flink, maar niet té braaf. Roosje gidst je met haar aparte blik langs de geijkte paadjes van de middenklasse.
copywriting_button: Contacteer mij!
---
{% include banner.html %}
<section id="bio" class="bg-primary">
    <div class="container">
        <div class="row pt-5">
            <div class="col-12 col-md-5 mb-5">
                <img src="img/bio.jpg" class="img-fluid pr-4 pl-4" alt="roosje-pertz-comedian">
            </div>
            <div class="col-12 col-md-7 mb-5 text-left text-white">
                <h2 class="section-heading">{{ page.bio_title }}</h2>
                <p class="text">
                    {{ page.bio_description }}
                </p>
                <a class="btn btn-light btn-xl text-white page-scroll" href="#podcast">{{ page.bio_button }}</a>
            </div>
        </div>
    </div>
</section>

<div id="socials" class="container p-5" style="top: -56px;">
  <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
    <div class="carousel-inner text-primary">
      <div class="carousel-item active">
        <a href="https://www.instagram.com/roosjepertz" class="col-10 col-md-9 col-lg-8 col-xl-6">
          <h2>{{ page.socials_instagram_title }}</h2>
          <!-- SnapWidget -->
          <script src="https://snapwidget.com/js/snapwidget.js"></script>
          <iframe src="https://snapwidget.com/embed/855834" class="snapwidget-widget" allowtransparency="true" frameborder="0" scrolling="no" style="border:none; overflow:hidden;  width:100%; "></iframe>
        </a>
      </div>
      <div class="carousel-item">
        <h2>{{ page.socials_twitter_title }}</h2>
        <a class="twitter-timeline" data-width="800" data-height="800" href="https://twitter.com/roosjepertz?ref_src=twsrc%5Etfw"></a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
      </div>
    </div>
    <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">{{ page.socials_twitter_previous }}</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">{{ page.socials_twitter_next }}</span>
    </a>
  </div>
</div>

<section class="bg-light " id="podcast">
  <div class="container banner pt-5" style="padding:unset; max-height: unset; background-image: url({{ '/img/Dertigerspraat.jpg' | relative_url }});">
    <div class="d-flex justify-content-center">
        <h2 class="text-white text-center bg-light mt-5 p-3">{{ page.podcast_title }}</h2>
    </div>
    <div class="container">
      <div class="row pb-5">
        <div class="col-0 col-md-1"></div>
        <div class="d-flex justify-content-center mt-4 col-12 col-md-10">
          <iframe style="max-width: 600px;" width="100%" height="600" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/users/450253833&color=%23f3dcdc&auto_play=false&hide_related=false&show_comments=false&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"></div>
        </div>
      </div>
    </div>
  </div>
</section>


<section id="copywriting" class="bg-light text-black" >
    <div class="container">
        <div class="row">
            <div class="col-12 col-md-7 text-left mt-5 mb-5">
                <h2 class="section-heading">{{ page.copywriting_title }}</h2>
                <p class="text"> {{ page.copywriting_text }}
                </p>
                <a class="btn btn-primary btn-xl text-white page-scroll" href="mailt: info@roosjepertz.be">{{ page.copywriting_button }}</a>
            </div>
            <div class="col-12 col-md-5 mt-5 mb-5">
                <img src="img/bio.jpg" class="img-fluid" alt="roosje-pertz-comedian">
            </div>
        </div>
    </div>
</section>

