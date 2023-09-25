<!DOCTYPE html>
<html lang="ru">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Исландия. Интересные факты</title>
  <link rel="stylesheet" href="css/style.css">
  <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
  <link rel="stylesheet" href="css/media.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
  <link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css" />
  <script type="text/javascript" src="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.min.js"></script>
</head>

<body>

  <div class="container-1" style="background-image: url(img/imgBackground\ 1.png);">
    <header>
      <div class="navbar">
        <div class="img__navbar">
          <img src="img/iconLogoWhite 1.png" alt="">
        </div>
        <div class="navbar__text">
          <p>Все факты</p>
          <p>Отзывы</p>
          <p>Контакты</p>
        </div>
        <div class="youtube__i" onclick="toggleNav()">
          <i class='bx bx-menu bx-lg' id="bx-menu"></i>
        </div>
      </div>

    </header>
    <div class="text__h1">

      <h1>Открой для себя новую</h1>
      <h1>Ирландию</h1>
    </div>
    <div class="text__h3">
      <h3>Авторские факты про Ирландию</h3>
    </div>
    <div class="video__active">
      <i class='bx bxl-youtube bx-lg'></i>

      <p class="video-active__text">Посмотрите
        видео про Исландию</p>


    </div>

    <div class="social-network">
      <div class="social-network__p">
        <p>Подписывайтесь на наши соцсети</p>
        <div class="icon__social-network">
          <i class='bx bxl-youtube bx-sm' id="icon__social"></i>
          <i class='bx bxl-facebook bx-sm' id="icon__social"></i>
          <i class='bx bxl-twitter bx-sm' id="icon__social"></i>
          <i class='bx bxl-vk bx-sm' id="icon__social"></i>
        </div>
      </div>
      <div class="main-social-network__img">
        <div class="social-network__img" id="media-img-1">
          <div class="social-network__img-1">
            <div class="number__img-1">
              02
            </div>
            <div class="information__img-1">
              <p>Водопады
                Ирландии</p>
              <i class='bx bx-right-arrow-alt bx-md'></i>

            </div>
            <img src="img/imgIsland 1.png" alt="">
          </div>
          <div class="social-network__img" id="social-network__img-none">
            <div class="social-network__img-1" id="media-img__2">
              <div class="number__img-1">
                03
              </div>
              <div class="information__img-1">
                <p>Сказочные Доломиты</p>
                <i class='bx bx-right-arrow-alt bx-md'></i>

              </div>
              <img src="img/imgIsland 3.png" alt="" id="social-network__img-2">
            </div>
          </div>
          <div class="social-network__img">
            <div class="social-network__img-1" id="media-img__3">
              <div class="number__img-1">
                04
              </div>
              <div class="information__img-1">
                <p>Неизведанная Норвегия</p>
                <i class='bx bx-right-arrow-alt bx-md'></i>

              </div>
              <img src="img/imgIsland 1 (2).png" alt="" id="social-network__img-3">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>


  <main>
    <div class="container-2">
      <div class="first__img">
        <img src="img/Ireland-1-Dublin-Castle-e1492141134646.jpg" alt="">
        <div class="text-img__1">
          <h2>Дублинский замок</h2>
          <p>Осматривать Ирландию большинство туристов начинают с территории города Дублина. Достопримечательности
            Ирландии в этом
            городе многочисленны, и одной из важнейших считается Дублинский замок.

            Этот удивительный памятник истории был основан в 1204 году. Он прекрасно сохранился до наших дней и до сих
            пор является
            главным замком Ирландии. Сегодня здесь располагается правительственный комплекс зданий.</p>

        </div>
      </div>

      <div class="second-img">

        <div class="text-img__2">
          <h2>Келлское аббатство</h2>
          <p>Келлское аббатство является одним из самых известных аббатств на территории Ирландии. Оно входит в список
            обязательных
            мест для тех, кто ищет, что посмотреть в Ирландии, за счет хорошей сохранности всех его зданий.</p>

        </div>

        <img src="img/Ireland-2-The-Abbey-of-Kells-e1492141310301.jpg" alt="">
      </div>
    </div>
    <div class="container-3">
      <div class="comments">
        <div class="comments__text">
          <button class="btn"><span>Читать отзывы</span></button>
        </div>
        <img src="img/9-Newgrange.jpg" alt="" class="img__container-3">
      </div>

    </div>
    <div class="carusel">
      <a href="https://platform.kodland.org/ru/courses/">
        <div class="carusel__item">
          <img src="img/RDRAOVOq6s4.jpg" alt="" class="image">
          <p class="title">Kodland</p>
        </div>
      </a>
      <a href="#">
        <div class="carusel__item">
          <img src="img/Русегэ.рф.jpg" alt="" class="image">
          <p class="title">Русегэ</p>
        </div>
      </a>
      <a href="https://www.youtube.com/">
        <div class="carusel__item">
          <img src="img/yt_1200.png" alt="" class="image">
          <p class="title">YouTube</p>
        </div>
      </a>
      <a href="https://www.apple.com/iphone-15-pro/">
        <div class="carusel__item">
          <img src="img/open_graph_logo.png" alt="" class="image">
          <p class="title">Iphone</p>
        </div>
      </a>
    </div>

  </main>

  <footer>
    <div class="container-5">
      <div class="logo">

        <img src="img/iconLogoDark 1.svg" alt="" ">
      </div>
      <div class=" text-1__footer">
        <p style="white-space: normal;">Политика
          конфиден.</p>
      </div>

      <div class="text-2__footer">
        <p style="white-space: normal;">Соглашение на обработку
          персональных данных</p>
      </div>
      <div class="icon__social-network-footer">
        <i class='bx bxl-youtube bx-sm' id="icon__social-1"></i>
        <i class='bx bxl-facebook bx-sm' id="icon__social-1"></i>
        <i class='bx bxl-twitter bx-sm' id="icon__social-1"></i>
        <i class='bx bxl-vk bx-sm' id="icon__social-1"></i>
      </div>

      <div class="icon__social-media">
        <i class='bx bxl-youtube bx-sm' id="icon__social-1-media"></i>
      </div>
      <div class="icon__social-media">
        <i class='bx bxl-facebook bx-sm' id="icon__social-1-media"></i>
      </div>
      <div class="icon__social-media">
        <i class='bx bxl-twitter bx-sm' id="icon__social-1-media"></i>
      </div>



    </div>

  </footer>

  <div class="nav__open-click" id="navElement">
    <div></div>
    <div class="navbar__text-open-click">
      <a href="#">
        <p>Все факты</p>
      </a>
    </div>
    <div class="navbar__text-open-click">
      <a href="#">
        <p>Отзывы</p>
      </a>
    </div>
    <div class="navbar__text-open-click">
      <a href="#">
        <p>Контакты</p>
      </a>
    </div>
  </div>

  <script src="Js/script.js"></script>
</body>

</html>
