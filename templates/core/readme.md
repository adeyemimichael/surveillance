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
{% comment %} flex  sm:block justify-between items-center  text-center  {% endcomment %}
{% comment %} flex-row  sm:block flex px-6 py-6  justify-center items-center {% endcomment %}
{% comment %} <div class="grid grid-cols-4 gap-4 md:grid-cols-2 lg:grid-cols-4 p-4 bg-gray-100 shadow-md rounded-md">
      <div class="col-span-2 md:col-span-1 lg:col-span-2 video-container bg-gray-100 p-4 rounded-md shadow-sm h-2/3">
        Video Livestream
      </div>
      <div class="button-controls bg-lavender-300 p-4 rounded-md shadow-sm">
        Button Controls
      </div>
      <div class="data-logs bg-lavender-400 p-4 rounded-md shadow-sm">
        Data Logs and Messages
      </div>
      <div class="timestamp bg-lavender-500 p-4 rounded-md shadow-sm">
        Timestamp or Calendar Stamp
      </div>
    </div> {% endcomment %}



    admin dashboard
