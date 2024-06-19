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
  </div>

  <div class="box2">
    <img src ="{% static 'images/image.jpg' %}" alt="image for the hero section is here "></img>
  </div>

</div>