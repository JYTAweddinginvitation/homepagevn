---
layout: home
home_text: request the pleasure of your company to celebrate our marriage
title: Junyoung + Thuc Anh
---

<head>
  <!-- Google Fonts for Noto Serif KR -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+KR:wght@200..900&display=swap" rel="stylesheet">

  <!-- Other metadata or stylesheets -->
</head>

<!-- Sticky Header with Navigation Links -->
<header class="sticky-header">
  <nav>
    <ul>
      <li><a href="#home">Trang chủ</a></li>
      <li><a href="#about">Thư mời</a></li>
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

  <hr style="margin-top: 30px;">

  <!-- About Section -->
  <section id="about">
    <h2 style="text-align: center;">Thư mời</h2>
    <div style="text-align: center;">
      <img src="{{'/img/about.jpeg' | relative_url }}" alt="img" style="width: 80%; max-width: 600px; height: auto;">
    </div>

    <div style="text-align: center;">
      <p>Chúng tôi tuy đến từ hai quốc gia khác nhau,</p>
      <p>nhưng nay chọn đồng hành cùng nhau</p>
      <p>trên hành trình phía trước.</p>
      <p>·</p>
      <p>Dù khác biệt về ngôn ngữ, văn hóa</p>
      <p>cũng như khoảng cách địa lý,</p>
      <p>nhưng cả hai quyết định sống bên nhau</p>
      <p>với sự thấu hiểu, tôn trọng,</p>
      <p>và yêu thương chăm sóc.</p>
      <p>·</p>
      <p>Chúng tôi trân trọng kính mời Quý vị</p>
      <p>đến dự buổi tiệc chung vui</p>
      <p>cùng gia đình chúng tôi</p>
      <p>tại khách sạn 
        <strong><a href="#location">La Vela Saigon</a></strong>
      </p>
      <p>Tầng 5, Sảnh Jupiter</p>
      <p>vào lúc 18:00</p>
      <p>thứ Bảy, ngày 11 tháng 1 năm 2025</p>
      <p style="font-style: italic;">nhằm ngày 12 tháng 12 năm Giáp Thìn</p>
      <p>·</p>
      <p>Sự hiện diện của Quý vị</p>
      <p>là niềm vinh hạnh cho gia đình chúng tôi</p>
      <p>Rất hân hạnh được đón tiếp</p>
      <p>Kính mời</p>

      <img src="/homepage/calender.jpg" alt="calender" style="width: 100%; max-width: 480px; height: auto; display: block; margin: 0 auto;">
    </div>
  </section>

  <div class="countdown-container">
    <p style="text-align: center;" id="countdown-message"></p>
  </div>

  <script>
    // Function to calculate and update the days left or passed
    function updateCountdown() {
      const weddingDate = new Date("January 11, 2025").getTime();
      const today = new Date().getTime();
      const timeDifference = weddingDate - today;

      const daysDifference = Math.ceil(timeDifference / (1000 * 60 * 60 * 24));

      let countdownMessage = "";
      if (daysDifference > 0) {
        countdownMessage = `Còn ${daysDifference} ngày nữa là đến ngày chúng tôi kết hôn!`;
      } else if (daysDifference === 0) {
        countdownMessage = "Hôm nay là ngày chúng tôi kết hôn!";
      } else {
        countdownMessage = `Đã ${Math.abs(daysDifference)} ngày trôi qua kể từ ngày chúng tôi kết hôn!`;
      }

      // Update the countdown display
      document.getElementById("countdown-message").textContent = countdownMessage;
    }

    // Call the function to update the countdown
    updateCountdown();
  </script>

  <hr>

  <!-- Gallery Section -->
  <section id="gallery">
    <h2 style="text-align: center;">Thư viện ảnh</h2>
    {% include_relative gallery.md %}
  </section>

  <hr>

  <!-- Location Section -->
  <section id="location">
    <h2 style="text-align: center;">Địa điểm</h2>
    <div style="text-align: center;">
      <img src="/homepage/mapimage.jpeg" alt="img" style="width: 80%; max-width: 600px; height: auto;">
    </div>

    <h3 style="text-align: center;">Khách sạn La Vela Saigon</h3>
    <h4 style="text-align: center;">Tầng 5</h4>
    <h4 style="text-align: center;">Sảnh Jupiter</h4>

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
    <h2 style="text-align: center;">Thông tin liên hệ</h2>
    {% include contact.html %}
  </section>

  <hr>

  <!-- Language Selection Section -->
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
