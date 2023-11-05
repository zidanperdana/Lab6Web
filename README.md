# Lab6Web

| Nama                            | NIM       | 
| :--------                       | :-------  |
| Maulana Zidan Perdana           | 312210463 |

<h1>Praktikum 6: Web Framework</h1>

<h2>Tujuan</h2>

1. Mahasiswa mampu memahami konsep dasar dari web framework.
2. Mahasiswa mampu memahami struktur dasar layout web menggunakan css framework.
3. Mahasiswa mampu memahami elemen-elemen css framework.

<h2>Instruksi Praktikum</h2>

1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama lab6_css_framework.
3. Buat file baru dokumen html.
4. Buat struktur dasar dari dokumen HTML.
5. Buatlah layout web sederhana menggunakan css framework (Twitter Bootstrap).
6. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org.

<h1>Twitter Bootstrap 5 (Bootstrap v5)</h1>

Twitter Bootstrap 5, atau Bootstrap v5, adalah kerangka kerja front-end open source yang digunakan untuk membangun situs web dan aplikasi web responsif. Dikembangkan oleh Twitter, Bootstrap menyediakan berbagai komponen dan gaya pradesain yang memudahkan pengembang dalam membangun tampilan yang menarik dan responsif dengan cepat. Bootstrap v5 adalah versi terbaru dari Bootstrap yang menghadirkan perbaikan, komponen baru, dan peningkatan performa. Ini sangat cocok untuk proyek-proyek pengembangan web modern.

<h2>Fitur Utama:</h2>

- Grid System yang Fleksibel: Bootstrap memungkinkan pembuatan tata letak yang responsif dengan mudah menggunakan grid system berbasis kolom.
- Komponen UI: Bootstrap menyediakan berbagai komponen UI seperti tombol, jumbotron, kartu, dan lainnya yang siap digunakan.
- Desain Responsif: Bootstrap mendukung desain responsif yang optimal, memastikan tampilan yang baik di berbagai perangkat dan resolusi layar.
- Kustomisasi Mudah: Anda dapat menyesuaikan tampilan Bootstrap sesuai dengan kebutuhan Anda dengan menggunakan variabel Sass dan alat-alat kustomisasi.
- Dokumentasi yang Kaya: Bootstrap dilengkapi dengan dokumentasi yang kaya dan contoh-contoh kode untuk membantu pengembang memahami dan menggunakannya dengan efisien.

Untuk informasi lebih lanjut, kunjungi situs resmi Bootstrap(https://getbootstrap.com/).

<h2>Struktur Dasar HTML Menggunakan Twitter Bootsrapt</h2>

    <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <title>Bootstrap demo</title>
        <link
          href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css"
          rel="stylesheet"
          integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN"
          crossorigin="anonymous"
        />
      </head>
      <body>
        <h1>Hello, world!</h1>
        <script
          src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"
          integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL"
          crossorigin="anonymous"
         ></script>
      </body>
    </html>
    
Dari sini kita melihat bahwa ada beberapa hal yang berbeda dari struktur dasar HTML biasa. yaitu adanya penamabahan tag <link> yang mengarah kepada tautan ke file CSS Bootstrap dan atribut-atribut yang terkait. yaitu sebagai berikut :

<h2>Stylesheet Bootstrap</h2>

![Screenshot 2023-11-05 194542](https://github.com/zidanperdana/Lab6Web/assets/116040175/c060fe28-3b88-4306-b909-e7e6fb7c9cdd)


<h2>Script Bootsrtapt</h2>

![Screenshot 2023-11-05 194557](https://github.com/zidanperdana/Lab6Web/assets/116040175/272b47db-3348-4f8c-a0c3-09efd94a3aa1)


<h2>Tugas Praktikum 6</h2>

Berdasarkan gambar layout web berikut, buatlah menggunakan Twitter Bootstrap.



HTML 
Untuk codenya 

    <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <title>Layout Sederhana</title>
        <link
          href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css"
          rel="stylesheet"
          integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN"
          crossorigin="anonymous"
        />
        <link rel="stylesheet" href="style.css" />
      </head>
      <body>
        <div
          id="container"
          class="m-0 m-auto"
          style="width: 980px; box-shadow: 0 0 1em #cccccc"
        >
          <header class="p-4">
            <h1 class="my-4 mx-2" style="color: #b5b5b5">Layout Sederhana</h1>
          </header>
          <nav class="d-block bg-primary">
            <a
              href="home.html"
              class="active py-3 px-5 d-inline-block text-white text-decoration-none fw-bold"
              >Home</a
            >
            <a
              href="artikel.html"
              class="py-3 px-5 d-inline-block text-white text-decoration-none fw-bold"
              >Artikel</a
            >
            <a
              href="about.html"
              class="py-3 px-5 d-inline-block text-white text-decoration-none fw-bold"
              >About</a
            >
            <a
              href="kontak.html"
              class="py-3 px-5 d-inline-block text-white text-decoration-none fw-bold"
              >Kontak</a
            >
          </nav>
          <section id="hero" class="bg-dark-subtle py-5 px-2 mb-3">
            <h1 class="mb-3 fs-5">Hello World!</h1>
            <p class="mb-3 fs-4 lh-5">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum
              lorem elit, iaculis innisl volutpat, malesuada tincidunt arcu. Proin
              in leo fringilla, vestibulum mi porta, faucibus felis. Integer
              pharetra est nunc, nec pretium nunc pretium ac.
            </p>
            <a href="home.html" class="btn btn-large">Learn more &raquo;</a>
          </section>
          <section id="wrapper" class="m-0">
            <section id="main" class="float-start p-2" style="width: 640px">
              <div class="row">
                <!-- box -->  

                <div
                  class="box d-block float-start py-0 px-2 text-center"
                  style="
                    width: 33.333333%;
                    box-sizing: border-box;
                    -moz-box-sizing: border-box;
                    -webkit-box-sizing: border-box;
                  "
                >
                  <img
                    src="https://dummyimage.com/120/db7d25/fff.png"
                    alt=""
                    class="image-circle border-0 align-middle"
                  />
                  <h3 class="my-2">Heading</h3>
                  <p class="lh-2 fs-5 mb-3">
                    Donec sed odio dui. Etiam porta sem malesuada magna mollis
                    euismod.
                  </p>
                  <a
                    href="#"
                    class="btn btn-default text-secondary-emphasis bg-dark-subtle"
                    >View detail</a
                  >
                </div>
                <div
                  class="box d-block float-start py-0 px-2 text-center"
                  style="
                    width: 33.333333%;
                    box-sizing: border-box;
                    -moz-box-sizing: border-box;
                    -webkit-box-sizing: border-box;
                  "
                >
                  <img
                    src="https://dummyimage.com/120/3e73e6/fff.png"
                    alt=""
                    class="image-circle border-0 align-middle"
                  />
              <h3 class="my-2">Heading</h3>
              <p class="lh-2 fs-5 mb-3">
                Donec sed odio dui. Etiam porta sem malesuada magna mollis
                euismod.
              </p>
              <a href="#" class="btn btn-default bg-dark-subtle">View detail</a>
            </div>
            <div
              class="box d-block float-start py-0 px-2 text-center"
              style="
                width: 33.333333%;
                box-sizing: border-box;
                -moz-box-sizing: border-box;
                -webkit-box-sizing: border-box;
              "
            >
              <img
                src="https://dummyimage.com/120/71e6d4/fff.png"
                alt=""
                class="image-circle border-0 align-middle"
              />
              <h3 class="my-2">Heading</h3>
              <p class="lh-2 fs-5 mb-3">
                Donec sed odio dui. Etiam porta sem malesuada magna mollis
                euismod.
              </p>
              <a href="#" class="btn btn-default bg-dark-subtle">View detail</a>
            </div>
          </div>
          <hr class="divider border-0 border-top my-5" />
          <!-- entry start -->
          <article class="entry my-4">
            <h2 class="mb-4">First featurette heading.</h2>
            <img
              src="https://dummyimage.com/150/7b8a70/fff.png"
              alt=""
              class="float-start rounded me-3"
            />
            <p style="line-height: 25px">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Vestibulum lorem elit, iaculis in nisl volutpat, malesuada
              tincidunt arcu. Proin in leo fringilla, vestibulum mi porta,
              faucibus felis. Integer pharetra est nunc, nec pretium nunc
              pretium ac.
            </p>
          </article>
          <hr class="divider border-0 border-top my-5" />

          <article class="entry my-4">
            <h2 class="mb-4">First featurette heading.</h2>
            <img
              src="https://dummyimage.com/150/7b8a70/fff.png"
              alt=""
              class="right-img float-end rounded me-3"
            />
            <p style="line-height: 25px">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Vestibulum lorem elit, iaculis in nisl volutpat, malesuada
              tincidunt arcu. Proin in leo fringilla, vestibulum mi porta,
              faucibus felis. Integer pharetra est nunc, nec pretium nunc
              pretium ac.
            </p>
          </article>
        </section>
        <section id="sidebar" class="float-start p-3" style="width: 260px">
          <aside id="sidebar" class="float-start p-3" style="width: 260px">
            <div class="widget-box border border-secondary mb-3">
              <h3
                class="title px-2 py-1 text-white"
                style="background-color: #428bca"
              >
                Widget Header
              </h3>
              <ul class="list-unstyled">
                <li class="border-bottom border-secondary-subtle">
                  <a href="#" class="py-2 px-2 d-block text-decoration-none"
                    >Widget Link</a
                  >
                </li>
                <li class="border-bottom border-secondary-subtle">
                  <a href="#" class="py-2 px-2 d-block text-decoration-none"
                    >Widget Link</a
                  >
                </li>
                <li class="border-bottom border-secondary-subtle">
                  <a href="#" class="py-2 px-2 d-block text-decoration-none"
                    >Widget Link</a
                  >
                </li>
                <li class="border-bottom border-secondary-subtle">
                  <a href="#" class="py-2 px-2 d-block text-decoration-none"
                    >Widget Link</a
                  >
                </li>
                <li class="border-bottom border-secondary-subtle">
                  <a href="#" class="py-2 px-2 d-block text-decoration-none"
                    >Widget Link</a
                  >
                </li>
              </ul>
            </div>
            <div class="widget-box border border-secondary mb-3">
              <h3
                class="title px-2 py-1 text-white"
                style="background-color: #428bca"
              >
                Widget Text
              </h3>
                  <p class="p-3 lh-5">
                    Vestibulum lorem elit, iaculis in nisl volutpat, malesuada
                    tincidunt arcu. Proin in leo fringilla, vestibulum mi porta,
                    faucibus felis. Integer pharetra est nunc, nec pretium nunc
                    pretium ac.
                  </p>
                </div>
              </aside>
            </section>
          </section>
          <footer class="bg-dark p-4 text-white">
            <p>&copy; 2021 - Universitas Pelita Bangsa</p>
          </footer>
        </div>
        <script
          src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"
          integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL"
          crossorigin="anonymous"
        ></script>
      </body>
    </html>


CSS 
Untuk codenya

    * {
        margin: 0;
        padding: 0;
      }
  
      body {
        line-height: 1;
        font-size: 100%;
        font-family: "Open Sans", sans-serif;
        color: #5a5a5a;
      }
      nav a.active,
      nav a:hover {
        background-color: #2b83ea;
      }
      .widget-box ul li a {
        color: #333;
      }
      .widget-box ul li:hover a {
        background-color: #eee;
      }
      .image-circle {
        border-radius: 50%;
      }
      .row {
        margin: 0 -10px;
        box-sizing: border-box;
        -moz-box-sizing: border-box;
        -webkit-box-sizing: border-box;
      }
      .row:after,
      .row:before,
      .entry:after,
      .entry:before {
        content: "";
        display: table;
      }
      .row:after,
      .entry:after {
        clear: both;
      }
      
      footer {
        clear: both;
      }
    
Screenshoot 

![Screenshot 2023-11-05 194235](https://github.com/zidanperdana/Lab6Web/assets/116040175/bb93f9e1-16df-4899-9653-9d51ad55f045)
![Screenshot 2023-11-05 194244](https://github.com/zidanperdana/Lab6Web/assets/116040175/1cb22b6d-f97e-4df9-bd07-b7a9d4891afd)


<h2>TERIMAKASIH</h2>
