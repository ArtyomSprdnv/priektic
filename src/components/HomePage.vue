<template>
  <router-view></router-view>
  <header class="mob-nav">
    <div class="container header">
      <div class="header-logo">
        <img src="@/assets/img/drupal-coder.svg" />
      </div>
      <div class="header-navigation">
        <nav>
          <ul class="header-nav-menu d-flex justify-content-between">
            <li class="header-nav-menu-item active">
              <a href="#">Поддержка Drupal</a>
            </li>
            <li class="header-nav-menu-item drop" id="Dropdown1">
              <a
                href="#"
                class="dropdown-toggle"
                role="button"
                data-bs-hover="dropdown"
                aria-expanded="false"
                id="Dropdown1"
                >Администрирование</a
              >
              <ul aria-labelledby="Dropdown1" class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Миграция</a></li>
                <li><a class="dropdown-item" href="#">Бэкапы</a></li>
                <li>
                  <a class="dropdown-item" href="#">Аудит Безопасности</a>
                </li>
                <li>
                  <a class="dropdown-item" href="#">Оптимизация скорости</a>
                </li>
                <li>
                  <a class="dropdown-item" href="#">Переезд на Https</a>
                </li>
              </ul>
            </li>
            <li class="header-nav-menu-item">
              <a href="#">Продвижение</a>
            </li>
            <li class="header-nav-menu-item"><a href="#">Реклама</a></li>
            <li class="header-nav-menu-item drop" id="Dropdown2">
              <a
                href="#"
                class="dropdown-toggle"
                role="button"
                id="Dropdown2"
                data-bs-toggle="dropdown"
                aria-expanded="false"
                >О нас</a
              >
              <ul aria-labelledby="Dropdown2" class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Наша команда</a></li>
                <li><a class="dropdown-item" href="#">Отдых</a></li>
                <li>
                  <a class="dropdown-item" href="#">Достижения</a>
                </li>
                <li>
                  <a class="dropdown-item" href="#">История</a>
                </li>
              </ul>
            </li>
            <li class="header-nav-menu-item"><a href="#">Проекты</a></li>
            <li class="header-nav-menu-item"><a href="#">Контакты</a></li>
          </ul>
        </nav>
      </div>
      <div class="btn-group dropup">
        <a
          role="button"
          class="nav-btn dropdown-toggle"
          data-bs-toggle="dropdown"
          aria-expanded="false"
        >
          <img src="@/assets/img/burger.svg" alt="" />
        </a>
        <ul class="dropdown-menu animate">
          <li><a class="dropdown-item active" href="#">Поддержка Drupal</a></li>
          <li>
            <a
              href="#"
              class="dropdown-item dropdown-toggle"
              role="button"
              id="Dropdown4"
              data-bs-toggle="dropdown"
              aria-expanded="false"
              >Администрирование
              <span> <img src="@/assets/img/caret.svg" alt=""/></span
            ></a>
            <ul aria-labelledby="Dropdown4" class="dropdown-menu show">
              <li><a class="dropdown-item" href="#">Миграция</a></li>
              <li><a class="dropdown-item" href="#">Бэкапы</a></li>
              <li>
                <a class="dropdown-item" href="#">Аудит Безопасности</a>
              </li>
              <li>
                <a class="dropdown-item" href="#">Оптимизация скорости</a>
              </li>
              <li>
                <a class="dropdown-item" href="#">Переезд на Https</a>
              </li>
            </ul>
          </li>
          <li><a class="dropdown-item" href="#">Продвижение</a></li>
          <li><a class="dropdown-item" href="#">Реклама</a></li>
          <li>
            <a
              href="#"
              class="dropdown-item dropdown-toggle"
              role="button"
              id="Dropdown3"
              data-bs-toggle="dropdown"
              aria-expanded="false"
              >О нас <span><img src="@/assets/img/caret.svg" alt=""/></span
            ></a>
            <ul aria-labelledby="Dropdown3" class="dropdown-menu show">
              <li><a class="dropdown-item" href="#">Наша команда</a></li>
              <li><a class="dropdown-item" href="#">Отдых</a></li>
              <li>
                <a class="dropdown-item" href="#">Достижения</a>
              </li>
              <li>
                <a class="dropdown-item" href="#">История</a>
              </li>
            </ul>
          </li>
          <li><a class="dropdown-item" href="#">Проекты</a></li>
          <li><a class="dropdown-item" href="#">Контакты</a></li>
        </ul>
      </div>
    </div>
  </header>
  <div class="main-info">
    <div class="main-info-video">
      <video autoplay="autoplay" muted preload="auto" loop playsinline>
        <source src="@/assets/img/video.mp4" type="video/mp4" />
      </video>
    </div>
    <div class="container d-flex justify-content-between">
      <div class="row">
        <div class="col-md-6">
          <h1 class="main-info-title">Поддержка <br />сайтов на Drupal</h1>
          <div class="main-info-desc">
            Сопровождение и поддержка сайтов<br />
            на CMS Drupal любых версий и запущенности
          </div>
          <div class="main-info-btn">
            <a href="#tariffs" class="main-btn">
              ТАРИФЫ
            </a>
          </div>
        </div>
        <div class="col-md-6">
          <div class="row main-list">
            <div class="col-md-4 col-sm-4 col-6 main-list-item">
              <div class="main-list-item-border">
                <div class="main-list-item-title">
                  #1
                  <img src="@/assets/img/cup.png" />
                </div>
                <div class="main-list-item-desc">
                  Drupal-разработчик в России по версии Рейтинга Рунета
                </div>
              </div>
            </div>
            <div class="col-md-4 col-sm-4 col-6 main-list-item">
              <div class="main-list-item-border">
                <div class="main-list-item-title">
                  3+
                </div>
                <div class="main-list-item-desc">
                  средний опыт специалистов более 3 лет
                </div>
              </div>
            </div>
            <div class="col-md-4 col-sm-4 col-6 main-list-item">
              <div class="main-list-item-border">
                <div class="main-list-item-title">
                  14
                </div>
                <div class="main-list-item-desc">
                  лет опыта в сфере Drupal
                </div>
              </div>
            </div>
            <div class="col-md-4 col-sm-4 col-6 main-list-item">
              <div class="main-list-item-border">
                <div class="main-list-item-title">
                  50+
                </div>
                <div class="main-list-item-desc">
                  модулей и тем в формате DrupalGive
                </div>
              </div>
            </div>
            <div class="col-md-4 col-sm-4 col-6 main-list-item">
              <div class="main-list-item-border">
                <div class="main-list-item-title">
                  90 000+
                </div>
                <div class="main-list-item-desc">
                  часов поддержки сайтов на Drupal
                </div>
              </div>
            </div>
            <div class="col-md-4 col-sm-4 col-6 main-list-item">
              <div class="main-list-item-border">
                <div class="main-list-item-title">
                  300+
                </div>
                <div class="main-list-item-desc">
                  Проектов на поддержке
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="main-utilities">
    <div class="container">
      <div class="col-md-6">
        <div class="row">
          <h2 class="util-label">
            13 лет совершенствуем<br />
            компетенции в Друпал<br />
            поддержке!
          </h2>
          <p class="util-low-label">
            Разрабатываем и оптимизируем модули, расширяем функциональность
            сайтов, обновляем дизайн
          </p>
        </div>
      </div>
      <div class="col-md-12 util-list">
        <div class="row d-flex">
          <div class="col-sm-3 col-6 util-body">
            <div class="util-bg">
              <img src="@/assets/img/competency-1.svg" class="img-fluid" />
            </div>
            <div class="util-title">
              Добавление<br />
              информации на сайт,<br />
              создание новых<br />
              разделов
            </div>
          </div>
          <div class="col-sm-3 col-6 util-body">
            <div class="util-bg">
              <img src="@/assets/img/competency-2.svg" class="img-fluid" />
            </div>
            <div class="util-title">
              Разработка и<br />
              оптимизация<br />
              модулей сайта
            </div>
          </div>
          <div class="col-sm-3 col-6 util-body">
            <div class="util-bg">
              <img src="@/assets/img/competency-3.svg" class="img-fluid" />
            </div>
            <div class="util-title">
              Интеграция с CRM,<br />
              1C, платежными<br />
              системами, любыми<br />
              веб-сервисами
            </div>
          </div>
          <div class="col-sm-3 col-6 util-body">
            <div class="util-bg">
              <img src="@/assets/img/competency-4.svg" class="img-fluid" />
            </div>
            <div class="util-title">
              Любые доработки<br />
              функционала<br />
              и дизайна
            </div>
          </div>
          <div class="col-sm-3 col-6 util-body">
            <div class="util-bg">
              <img src="@/assets/img/competency-5.svg" class="img-fluid" />
            </div>
            <div class="util-title">
              Аудит и мониторинг<br />
              безопасности Drupal<br />
              сайтов
            </div>
          </div>
          <div class="col-sm-3 col-6 util-body">
            <div class="util-bg">
              <img src="@/assets/img/competency-6.svg" class="img-fluid" />
            </div>
            <div class="util-title">
              Миграция, импорт<br />
              контента и апгрейд<br />
              Drupal
            </div>
          </div>
          <div class="col-sm-3 col-6 util-body">
            <div class="util-bg">
              <img src="@/assets/img/competency-7.svg" class="img-fluid" />
            </div>
            <div class="util-title">
              Оптимизация<br />
              и ускорение<br />
              Drupal-сайтов
            </div>
          </div>
          <div class="col-sm-3 col-6 util-body">
            <div class="util-bg">
              <img src="@/assets/img/competency-8.svg" class="img-fluid" />
            </div>
            <div class="util-title">
              Веб-маркетинг,<br />
              консультации<br />
              и работы по SEO
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="main-tarrifs">
    <div class="container" id="tariffs">
      <div class="col-md-12">
        <div class="row text-center">
          <h2 class="tariffs-label">Тарифы</h2>
        </div>
      </div>
      <div class="col-md-12">
        <div class="row tariff-list">
          <div class="col-md-4 col-12 col-12 tariff-item">
            <div class="tariff-header">
              <div class="tariff-name">
                Стартовый
                <hr />
              </div>
            </div>
            <div class="tariff-desc">
              <p>Консультации и работы по SEO</p>
              <p>Услуги дизайнера</p>
              <p>
                Неиспользованные<br />
                оплаченные часы переносятся<br />
                на следующий месяц
              </p>
              <p>
                Предоплата от 6000 рублей в<br />
                месяц
              </p>
            </div>
            <div class="tariff-btn text-align-center">
              <router-link to="/form">Свяжитесь с нами!</router-link>
            </div>
          </div>
          <div class="col-md-4 col-12 col-12 tariff-item active">
            <div class="tariff-header">
              <div class="tariff-name">
                Бизнес
                <hr />
              </div>
            </div>
            <div class="tariff-desc">
              <p>Консультации и работы по SEO</p>
              <p>Услуги дизайнера</p>
              <p>
                Высокое время редакции - до 2 <br />
                рабочих дней
              </p>
              <p>
                Неиспользованные<br />
                оплаченные часы не<br />
                переносятся
              </p>
              <p>
                Предоплата от 30000 рублей в<br />
                месяц
              </p>
            </div>
            <div class="tariff-btn text-align-center">
              <router-link to="/form">Свяжитесь с нами!</router-link>
            </div>
          </div>
          <div class="col-md-4 col-12 col-12 tariff-item">
            <div class="tariff-header">
              <div class="tariff-name">
                VIP
                <hr />
              </div>
            </div>
            <div class="tariff-desc">
              <p>Консультации и работы по SEO</p>
              <p>Услуги дизайнера</p>
              <p>
                Максимальное время реакции<br />
                - в день обращения
              </p>
              <p>
                Неиспользованные<br />
                оплаченные часы не<br />
                переносятся
              </p>
              <p>
                Предоплата от 270 000 рублей в<br />
                месяц
              </p>
            </div>
            <div class="tariff-btn text-align-center">
              <router-link to="/form">Свяжитесь с нами!</router-link>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-12">
        <div class="row text-center tariff-main-desc">
          <p>
            Вам не подходят наши тарифы? Оставьте заявку и мы <br />
            предложим вам индивидуальные условия!
          </p>
        </div>
        <div class="row text-center tariff-main-btn">
          <div class="tariff-a">
            <a href="#">Получить индивидуальный тариф</a>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="main-reviews">
    <div class="container">
      <div class="col-md-12">
        <div class="row text-center">
          <h2 class="reviews-label">
            Отзывы
          </h2>
        </div>
      </div>
      <div class="col-md-12">
        <div class="container">
          <div class="reviews-container">
            <div class="carousel-wrapper">
              <Reviews v-bind:reviewsSliderItems="reviewsSliderItems" />
              <div class="carousel-nav">
                <div class="reviews-nav">
                  <span class="reviews-counter"></span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <footer>
    <div class="container">
      <div class="col-12">
        <div class="row footer-container">
          <div class="col-md-6 col-12">
            <div class="row">
              <div class="footer-block">
                <div class="footer-header">
                  Оставить заявку на <br />
                  поддержку сайта
                </div>
                <div class="footer-desc">
                  Срочно нужна поддержка сайта? Ваша команда не успевает<br />
                  справиться самостоятельно или предыдущий подрядчик не<br />
                  справился с работой? Тогда вам точно к нам! Просто оставьте<br />
                  заявку и наш менеджер с вами свяжется!
                </div>
                <div class="footer-contacts">
                  <div class="footer-tel">
                    <a href="#">8 800 222-26-73</a>
                  </div>
                  <div class="footer-mail">
                    <a href="#">info@drupal-coder.ru</a>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-12">
            <Form />
          </div>
        </div>
      </div>
      <div class="col-12 footer-social">
        <div class="row">
          <div class="col-md-6 col-12">
            <div class="row">
              <div class="social-block">
                <ul class="social-list">
                  <li class="social-list-item">
                    <a href="#"
                      ><img src="@/assets/img/facebook.svg" alt=""
                    /></a>
                  </li>
                  <li class="social-list-item">
                    <a href="#"><img src="@/assets/img/vk.svg" alt="" /> </a>
                  </li>
                  <li class="social-list-item">
                    <a href="#"
                      ><img src="@/assets/img/telegram.svg" alt=""
                    /></a>
                  </li>
                  <li class="social-list-item">
                    <a href="#"><img src="@/assets/img/youtube.svg" alt=""/></a>
                  </li>
                </ul>
                <div class="social-desc">
                  <p>
                    Проект ООО «Инитлаб», Краснодар, Россия.<br />
                    Drupal является зарегистрированной торговой маркой Dries
                    Buytaert.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>
<script>
import Carousel from "./Carousel.vue";
import Reviews from "./Reviews.vue";
import Form from "./Form.vue";
var globalID;
export default {
  components: { Carousel, Reviews, Form },
  data() {
    return {
      reviewsSliderItems: [
        {
          id: 1,
          img: "logo_0.png",
          text: `Долгие поиски единственного и неповторимого мастера на
                      многострадальный сайт www.cielparfum.com, который был
                      собран крайне некомпетентным программистом и раз в месяц
                      стабильно грозил погибнуть, привели меня на сайт и, в
                      итоге, к ребятам из Drupal-coder. И вот уже практически
                      полгода как не проходит и дня, чтобы я не поудивлялась и
                      не порадовалась своему везению! Починили все, что не
                      работало - от поиска до отображения меню. Провели редизайн
                      - не отходя от желаемого, но со своими существенными и
                      качественными дополнениями. Осуществили ряд проектов -
                      конкурсы, тесты и тд. А уж мелких починок и доработок - не
                      счесть! И главное - все качественно и быстро (не взирая на
                      не самый "быстрый" тариф). Есть вопросы - замечательный
                      Алексей всегда подскажет, поддержит, отремонтирует и/или
                      просто сделает с нуля. Есть задумка для реализации -
                      замечательный Сергей обсудит и предложит идеальный
                      вариант. Есть проблема - замечательные Надежда и Роман
                      починят, поправят, сделают! Ребята доказали, что эта CMS -
                      мощная и грамотная система управления. Надеюсь, что наше
                      сотрудничество затянется надолго! Спасибо!!!`,
          author: `С уважением, Наталья Сушкова руководитель Отдела
                    веб-проектов Группы компаний «Си Эль парфюм»`
        },
        {
          id: 2,
          img: "logo_0.png",
          text: `Долгие поиски единственного и неповторимого мастера на
                      многострадальный сайт www.cielparfum.com, который был
                      собран крайне некомпетентным программистом и раз в месяц
                      стабильно грозил погибнуть, привели меня на сайт и, в
                      итоге, к ребятам из Drupal-coder. И вот уже практически
                      полгода как не проходит и дня, чтобы я не поудивлялась и
                      не порадовалась своему везению! Починили все, что не
                      работало - от поиска до отображения меню. Провели редизайн
                      - не отходя от желаемого, но со своими существенными и`,
          author: `С уважением, Наталья Сушкова руководитель Отдела
                    веб-проектов Группы компаний «Си Эль парфюм»`
        },
        {
          id: 3,
          img: "logo_2.png",
          text: `Долгие поиски единственного и неповторимого мастера на
                      многострадальный сайт www.cielparfum.com, который был
                      собран крайне некомпетентным программистом и раз в месяц
                      стабильно грозил погибнуть, привели меня на сайт и, в
                      итоге, к ребятам из Drupal-coder. И вот уже практически
                      полгода как не проходит и дня, чтобы я не поудивлялась и
                      не порадовалась своему везению! Починили все, что не
                      работало - от поиска до отображения меню. Провели редизайн
                      - не отходя от желаемого, но со своими существенными и`,
          author: `С уважением, Наталья Сушкова руководитель Отдела
                    веб-проектов Группы компаний «Си Эль парфюм»`
        },
        {
          id: 4,
          img: "logo-estee.png",
          text: `Долгие поиски единственного и неповторимого мастера на
                      многострадальный сайт www.cielparfum.com, который был
                      собран крайне некомпетентным программистом и раз в месяц
                      стабильно грозил погибнуть, привели меня на сайт и, в`,
          author: `С уважением, Наталья Сушкова руководитель Отдела
                    веб-проектов Группы компаний «Си Эль парфюм»`
        },
        {
          id: 5,
          img: "logo.png",
          text: `Долгие поиски единственного и неповторимого мастера на
                      многострадальный сайт www.cielparfum.com, который был
                      собран крайне некомпетентным программистом и раз в месяц
                      стабильно грозил погибнуть, привели меня на сайт и, в
                      итоге, к ребятам из Drupal-coder. И вот уже практически
                      полгода как не проходит и дня, чтобы я не поудивлялась и
                      не порадовалась своему везению! Починили все, что не
                      работало - от поиска до отображения меню. Провели редизайн
                      - не отходя от желаемого, но со своими существенными и`,
          author: `С уважением, Наталья Сушкова руководитель Отдела
                    веб-проектов Группы компаний «Си Эль парфюм»`
        },
        {
          id: 6,
          img: "lpcma_rus_v4.jpg",
          text: `Долгие поиски единственного и неповторимого мастера на
                      многострадальный сайт www.cielparfum.com, который был
                      собран крайне некомпетентным программистом и раз в месяц
                      стабильно грозил погибнуть, привели меня на сайт и, в
                      итоге, к ребятам из Drupal-coder. И вот уже практически
                      полгода как не проходит и дня, чтобы я не поудивлялась и
                      не порадовалась своему везению! Починили все, что не
                      работало - от поиска до отображения меню. Провели редизайн
                      - не отходя от желаемого, но со своими существенными и`,
          author: `С уважением, Наталья Сушкова руководитель Отдела
                    веб-проектов Группы компаний «Си Эль парфюм»`
        },
        {
          id: 7,
          img: "nashagazeta_ch.png",
          text: `Долгие поиски единственного и неповторимого мастера на
                      многострадальный сайт www.cielparfum.com, который был
                      собран крайне некомпетентным программистом и раз в месяц
                      стабильно грозил погибнуть, привели меня на сайт и, в
                      итоге, к ребятам из Drupal-coder. И вот уже практически
                      полгода как не проходит и дня, чтобы я не поудивлялась и
                      не порадовалась своему везению! Починили все, что не
                      работало - от поиска до отображения меню. Провели редизайн
                      - не отходя от желаемого, но со своими существенными и
                      Lorem ipsum dolor sit amet consectetur adipisicing elit.
                      Tempore recusandae voluptatibus officiis.`,
          author: `С уважением, Наталья Сушкова руководитель Отдела
                    веб-проектов Группы компаний «Си Эль парфюм»`
        },
        {
          id: 8,
          img: "logo_0.png",
          text: `Долгие поиски единственного и неповторимого мастера на
                      многострадальный сайт www.cielparfum.com, который был
                      собран крайне некомпетентным программистом и раз в месяц
                      стабильно грозил погибнуть, привели меня на сайт и, в
                      итоге, к ребятам из Drupal-coder.`,
          author: `С уважением, Наталья Сушкова руководитель Отдела
                    веб-проектов Группы компаний «Си Эль парфюм»`
        }
      ]
    };
  },
  methods: {
    repeatOften() {
      let trans = parseInt(
        $(".modal-body")
          .css("transform")
          .split(",")[4]
      );
      if (trans < 0) {
        $(".modal-body").css({
          transform: `translateX(${trans + 10}px)`
        });
      } else {
        cancelAnimationFrame(globalID);
      }
      globalID = requestAnimationFrame(this.repeatOften);
    }
  },
  mounted() {
    $(".header-nav-menu-item.drop").on("mouseover", function(e) {
      let id = this.id;
      $(`[aria-labelledby=${id}]`).addClass("show");
    });
    $(`.header-nav-menu-item.drop`).on("mouseout", function(e) {
      let id = this.id;
      $(`[aria-labelledby=${id}]`).removeClass("show");
    });
    $(".btn-group").on("show.bs.dropdown", function(e) {
      $(".dropdown-menu").removeClass("invisible");
      $(this)
        .find(".dropdown-menu")
        .first()
        .removeClass("slideOut")
        .stop(true, true)
        .addClass("slideIn");
    });
    $(".btn-group").on("hide.bs.dropdown", function(e) {
      e.preventDefault();
      $(this)
        .find(".dropdown-menu")
        .first()
        .removeClass("slideIn")
        .stop(true, true)
        .addClass("slideOut");
      setTimeout(() => {
        $(".nav-btn").removeClass("show");
        $(".animate").removeClass("show");
      }, 300);
    });
  },
  watch: {
    $route(to, from) {
      if (to.path == "/form") {
        globalID = requestAnimationFrame(this.repeatOften);
      } else {
        cancelAnimationFrame(globalID);
      }
    }
  }
};
</script>

<style>
.route-enter-from {
  opacity: 0;
}
.route-enter-active {
  transition: all 0.3s ease-out;
}
.route-leave-to {
  opacity: 0;
}
.route-leave-active {
  transition: all 0.3s ease-in;
}
</style>
