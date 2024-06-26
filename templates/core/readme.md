<div class="main-div">
  <div class="box-1">
    <div class="header-div">
    <h1 class="text-lg">Welcome to the UilCpe Surveillance System Project </h1>
    </div>
  
    <div class="all-btn">
      <a href="{% url 'moderator_reg' %}" id="second" class="font-bold text-8xl">Admin Register</a>
      <a href="{% url 'moderator_login' %}" id="first">Admin Login</a>
      <a href="{% url 'visitor_reg' %}" id="fourth" >Guest Register</a>
      <a href="{% url 'visitor_login' %}" id="third">Guest Login</a>
    </div>
    <script src="https://unpkg.com/@dotlottie/player-component@latest/dist/dotlottie-player.mjs" type="module"></script> 

  <dotlottie-player src="https://lottie.host/9eda9868-11fc-4dd9-9b9d-edc6d504391e/HtUw0cR04o.json" background="transparent" speed="1" style="width: 700px; height: 700px;" loop autoplay></dotlottie-player>
  </div>

  <div class="box2">
    <img src ="{% static 'images/image.jpg' %}" alt="image for the hero section is here "></img>
  </div>

</div>