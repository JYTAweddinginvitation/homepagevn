---
layout: home
home_text: request the pleasure of your company to celebrate our marriage
title: Junyoung + Thuc Anh
---

<!-- Sticky Header with Navigation Links -->
<header class="sticky-header">
    <nav>
        <ul>
<li><a href="#home">Trang chủ</a></li>
<li><a href="#about">Giới thiệu</a></li>
<li><a href="#gallery">Thư viện</a></li>
<li><a href="#location">Địa điểm</a></li>
<li><a href="#contact">Liên hệ</a></li>
        </ul>
    </nav>
</header>

<div class="container">
    <!-- Home Section -->
    <section id="home">
        {% include home.html %}
    </section>

<hr style="margin-top: 40px;">

    <!-- About Section -->
    <section id="about">
        <h2 style="text-align: center;">Giới thiệu</h2>
        <div style="text-align: center;">
            <img src="{{'/img/about.jpeg' | relative_url }} " alt="img" style="width: 80%; max-width: 600px; height: auto;">
        </div>

        <div style="text-align: center;">
 <p>Kính mời bạn đến tham dự</p>
<p></p>
<p>lễ cưới của chúng tôi</p>
<p></p>
<p>vào <strong>thứ Bảy, ngày 11 tháng 1 năm 2025</strong></p>
<p></p>
<p>lúc <strong>7 giờ tối</strong></p>
<p></p>
<p>tại <strong><a href="#location">La Vela Saigon</a></strong></p>
<p></p>
<p>Tầng 5, Sảnh Jupiter</p>
<p></p>
<p>tiếp theo là lễ cắt bánh</p>
<p></p>
<p>và khiêu vũ đến khuya</p>
<p></p>
<p>Vui lòng xác nhận tham dự (RSVP)</p>
        </div>
    </section>

  <hr>

    <!-- Gallery Section -->
    <section id="gallery">
        <h2 style="text-align: center;">Thư viện</h2>
        {% include_relative gallery.md %}
    </section>

  <hr>

    <!-- Location Section -->
    <section id="location">
        <h2 style="text-align: center;">Địa điểm</h2>
        <div style="text-align: center;">
            <img src="/homepage/mapimage.jpeg" alt="img" style="width: 80%; max-width: 600px; height: auto;">
        </div>

        <h3 style="text-align: center;">LA VELA SAIGON HOTEL</h3>
        <h4 style="text-align: center;">5th floor</h4>
        <h4 style="text-align: center;">Jupiter Hall</h4>

        <p style="text-align: center;"><a href="tel:+8402836222280">Tel: +84 (0) 28 3622 2280</a></p>
        <p style="text-align: center;"><a href="mailto:lavelahotel@lavelasaigon.com">Email: lavelahotel@lavelasaigon.com</a></p>
        <p style="text-align: center;"><a href="https://lavelasaigon.com/">Website</a></p>

        <p style="text-align: center;">
            <a href="https://www.google.co.kr/maps/place/%EB%9D%BC+%EB%B2%A8%EB%9D%BC+%EC%82%AC%EC%9D%B4%EA%B3%B5+%ED%98%B8%ED%85%94/@10.7886761,106.6828959,17z/data=!3m1!4b1!4m9!3m8!1s0x31752f2d1f5cd9e7:0xd2284b6940329fcf!5m2!4m1!1i2!8m2!3d10.7886708!4d106.6854708!16s%2Fg%2F11h9kpyf0z?hl=ko&entry=ttu">
                <strong>GOOGLE MAP</strong>
            </a>
        </p>

        <script>
            console.log("We look forward to celebrating with you!");
            console.log("Join us at La Vela Hotel on January 11, 2025, at 7 PM for a day to remember");
        </script>
    </section>

  <hr>

    <!-- Contact Section -->
    <section id="contact">
        <h2 style="text-align: center;">Liên hệ</h2>
        {% include contact.html %}   
    </section>


   <hr>
<!-- Add this after the last <hr> -->
<section id="language-selection">
    <h3 style="text-align: center;">Language</h3>
    <div style="text-align: center;">
        <a href="https://jytaweddinginvitation.github.io/homepagekr/">
            <img src="/homepage/img/kr.JPG" alt="Korean Language" style="width: 35px; height: 35px; margin-right: 10px;">
        </a>
        <a href="https://jytaweddinginvitation.github.io/homepage/">
            <img src="/homepage/img/eng.JPG" alt="English Language" style="width: 35px; height: 35px; margin-right: 10px;">
        </a>
        <a href="https://jytaweddinginvitation.github.io/homepagevn/">
            <img src="/homepage/img/vn.JPG" alt="Vietnamese Language" style="width: 35px; height: 35px;">
        </a>
    </div>
</section>
   
</div>

<!-- Additional Styling -->
<style>
    /* Center-align section titles */
    section h2 {
        text-align: center;
    }

    /* Change hyperlink color to black */
    a {
        color: black;
        text-decoration: none; /* Optional: Remove underline */
    }

    a:hover {
        text-decoration: underline; /* Optional: Add underline on hover */
    }
</style>
