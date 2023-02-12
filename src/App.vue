<template>
  <div class="wrapper">
    <div class="wrapper-content">
      <section>
        <div class="container">
          <div id="app">
            <h2>form JET</h2>
            <form action="" class="form">
              <div class="form__choice">
                <a href="" class="form__choice-btn email">E-mail</a>
                <a href="" class="form__choice-btn phone">Номер телефона</a>
              </div>
              <div class="form__mail">
                <input type="email" class="form__input email">
                <label for="" class="form__input-label">E-mail</label>
              </div>  
              <div class="form__phone">
                <input type="phone" class="form__input phone">
                <label for="" class="form__input-label">Телефон</label>
              </div>  
              <div class="form__password">
                <input type="password" class="form__input password">
                <label for="" class="form__input-label">Пароль</label>
                <a href="#" class="password-control"><i class="fa-solid fa-eye"></i></a>
                <div class="form__input-error">Введите пароль</div>
              </div>  
              <div class="form__input countries">
                <div class="countries__header">
                  Выберите страну
                </div>
                <ul class="countries__list">
                  <li class="countries__item">
                    <img src="https://cdn-icons-png.flaticon.com/512/555/555417.png" alt="" class="countries__flag">
                    <div class="countries__title">Англия</div>
                  </li>
                  <li class="countries__item">
                    <img src="https://cdn-icons-png.flaticon.com/512/555/555613.png" alt="" class="countries__flag">
                    <div class="countries__title">Германия</div>
                  </li>
                  <li class="countries__item">
                    <img src="https://cdn-icons-png.flaticon.com/512/555/555571.png" alt="" class="countries__flag">
                    <div class="countries__title">Польша</div>
                  </li>
                  <li class="countries__item">
                    <img src="https://cdn-icons-png.flaticon.com/512/206/206724.png" alt="" class="countries__flag">
                    <div class="countries__title">Испания</div>
                  </li>
                  <li class="countries__item">
                    <img src="https://cdn-icons-png.flaticon.com/512/206/206727.png" alt="" class="countries__flag">
                    <div class="countries__title">Финляндия</div>
                  </li>
                </ul>
              </div>
              <div class="form__input currencies">
                <div class="currencies__header default">
                  Выберите валюту
                </div>
                <ul class="currencies__list">
                  <li class="currencies__item">
                    <div class="currencies__title">Английский фунт</div>
                  </li>
                <li class="currencies__item">
                    <div class="currencies__title">Немецкая марка</div>
                  </li>
                  <li class="currencies__item">
                    <div class="currencies__title">Злотый</div>
                  </li>
                  <li class="currencies__item">
                    <div class="currencies__title">Евро</div>
                  </li>
                  <li class="currencies__item">
                    <div class="currencies__title">Финляндская марка</div>
                  </li>
                </ul>
              </div>
              <button class="form__btn">
                Зарегистрироваться
              </button>
            </form>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script>

export default {
  // data: {
  //   title: 'Form JET'
  // }
}
</script>

<style>
</style>
