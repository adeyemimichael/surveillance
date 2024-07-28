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

         {% comment %} <script>
            function toggleMenu() {
                var menu = document.getElementById("mobile-menu");
                if (menu.style.display === "block") {
                    menu.style.display = "flex";
                } else {
                    menu.style.display = "block";
                }
            }
        </script> {% endcomment %}

         {% comment %} <li><a href="#about" class ="p-3  hover:text-blue-900">About</a></li>
                  <li><a href="#" class ="p-3 hover:text-blue-900">Services</a></li>
                  <li><a href="#" class ="p-3 hover:text-blue-900 mb-4 md:mb-0">Contact</a></li> {% endcomment %}

                  .navitems ul li a.bg-blue {
                    background-color: #1e40af;
                    color: white;
                    border-radius: 9999px;
                    padding: 8px 32px;
                    text-align: center;
                  }
                  .navitems ul li a.bg-blue:hover {
                    background-color: #3b82f6;
                  }
                  <svg data-v-423bf9ae="" xmlns="http://www.w3.org/2000/svg" 
          viewBox="0 0 404 90" class="iconLeft fill-current w-auto h-10" ><!----><!----><!---->
          <g data-v-423bf9ae="" id="0587cefe-1626-49c3-9862-b99936c16411" fill="#000000" transform="matrix(5.741626899055351,0,0,5.741626899055351,109.6297589728666,-6.244019085031169)">
            <path d="M0.29 13.10C1.04 13.78 2.20 14.14 3.29 14.14C4.79 14.14 6.15 13.45 6.15 11.93C6.16 9.23 2.20 9.97 2.20 8.60C2.20 8.06 2.66 7.85 3.29 7.85C3.95 7.85 4.77 8.11 5.43 8.51L6.02 7.32C5.35 6.85 4.35 6.57 3.42 6.57C1.99 6.57 0.67 7.21 0.67 8.72C0.66 11.41 4.58 10.56 4.58 12.08C4.58 12.64 4.05 12.88 3.36 
            12.88C2.55 12.88 1.51 12.53 0.87 11.96ZM7.53 11.27C7.53 13.05 8.55 14.14 10.26 14.14C11.48 14.13 12.42 13.66 12.92 
            12.63L12.92 14.08L14.53 14.08L14.53 6.64L12.92 6.64L12.92 10.30C12.92 11.61 12.17 12.60 10.88 12.63C9.80 12.63 9.14 
            11.94 9.14 10.82L9.14 6.64L7.53 6.64ZM15.74 6.64L18.62 14.08L20.29 14.08L23.14 6.64L21.53 6.64L19.49 12.50L17.42 6.64ZM23.56 10.37C23.56 12.61 25.07 14.14 27.37 14.14C28.66 14.14 29.72 13.68 30.45 12.88L29.60 11.97C29.05 12.53 28.31 12.84 27.50 12.84C26.32 12.84 25.44 12.12 25.19 10.98L30.81 
            10.98C31.01 8.29 29.95 6.58 27.33 6.58C25.12 6.59 23.56 8.12 23.56 10.37ZM25.16 9.80C25.34 8.61 26.17 7.87 27.34 7.87C28.56 7.87 29.36 8.60 29.41 9.80ZM32.56 14.08L34.17 14.08L34.17 3.70L32.56 3.70ZM36.01 11.84C36.01 13.16 37.02 14.15 38.63 14.15C39.70 14.15 40.56 13.83 41.09 13.17L41.09 14.08L42.67 14.08L42.66 9.20C42.64 7.56 41.57 6.58 39.65 6.58C38.23 6.58 37.48 6.90 36.44 7.52L37.10 8.64C37.84 8.13 38.58 7.88 39.30 7.88C40.47 7.88 41.08 8.44 41.08 9.38L41.08 9.60L38.82 9.60C37.03 9.62 36.01 10.49 36.01 11.84ZM37.52 11.77C37.52 11.06 38.01 10.78 39.06 10.78L41.08 10.78L41.08 11.47C40.99 12.28 40.11 12.88 38.96 12.88C38.07 12.88 37.52 12.45 37.52 11.77ZM43.83 14.08L45.63 14.08L47.53 11.35L49.31 14.08L51.16 14.08L48.59 10.26L50.99 6.64L49.22 6.64L47.53 9.18L45.86 6.64L44.02 6.64L46.47 10.26Z"></path></g><defs data-v-423bf9ae=""><linearGradient data-v-423bf9ae="" 
              gradientTransform="rotate(25)" id="8be094d5-90a1-47b7-9b49-c107eb0c60c7" x1="0%" y1="0%" x2="100%" y2="0%"><stop data-v-423bf9ae="" offset="0%" 
              style="stop-color: rgb(40, 139, 88); stop-opacity: 1;"></stop>
              <stop data-v-423bf9ae="" offset="100%" style="stop-color: rgb(21, 34, 241); stop-opacity: 1;"></stop>
            </linearGradient></defs><g data-v-423bf9ae="" id="7895d473-d1c4-40d2-89c5-9c4abdfbc911" transform="matrix(2.852072528086791,0,0,2.852072528086791,0.3618419448213217,-0.41116010653409063)" stroke="none" fill="url(#8be094d5-90a1-47b7-9b49-c107eb0c60c7)">
              <path d="M16 23.787L8.102 16 16 8.213 23.898 16 16 23.787zM9.525 16L16 22.383 22.475 16 16 9.617 9.525 16z"></path><path d="M15.915 31.778L-.005 16.084 16.085.222l15.92 15.694-16.09 15.862zM1.419 16.084l14.496 14.29 14.666-14.458-14.496-14.29L1.419 16.084z"></path><path d="M15.5.924h1v30.152h-1z"></path></g><!---->
            </svg>



            <button class="focus:text-blue-700 hover:text-blue-500 px-6 py-4 ">
              <svg class="h-6 w-6  fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><path d="M16 132h416c8.8 0 16-7.2 16-16V76c0-8.8-7.2-16-16-16H16C7.2 60 0 67.2 
                0 76v40c0 8.8 7.2 16 16 16zm0 160h416c8.8 0 16-7.2 16-16v-40c0-8.8-7.2-16-16-16H16c-8.8 0-16 7.2-16 16v40c0 8.8 7.2 16 16 16zm0 160h416c8.8 0 16-7.2 16-16v-40c0-8.8-7.2-16-16-16H16c-8.8 0-16 7.2-16 16v40c0 8.8 7.2 16 16 16z"/></svg>
              </button>


              <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>ADMIN DASHBOARD</title>
    <style>
        /* Add your CSS styles here */
    </style>
</head>
<body>
{% if is_moderator %}
    <div class="admin-dashboard">
        <h1 class="text-center font-bold head-tag p-96">Admin Dashboard</h1>
        <h2>Welcome, {{ user.username }}</h2>
        {% comment %} <h2>Welcome, {{ voter.user.username }}</h2> {% endcomment %}
        
        
        <div class="video-stream">
            <h1>VIDEO LIVE STREAM</h1>
            <div>
                <h2>Camera Stream</h2>
                <img src="{% url 'webcam' %}" width="640" height="480" alt="feeds">
            </div>
        </div>
        
        <div class="past-recordings">
            <h2>Past Recordings</h2>
            <ul>
                {% for recording in recordings %}
                    <li>
                        <a href="{% url 'play_recording' recording.id %}">{{ recording.timestamp }}</a>
                    </li>
                {% endfor %}
            </ul>
        </div>
        
        <div class="visitors">
            <h2>Visitor Authorization</h2>
            <ul>
                {% for visitor in visitors %}
                    <li>
                        <p>{{ visitor.user.username }} is 
                            {% if visitor.is_authorized %}
                                authorized
                            {% else %}
                                unauthorized
                            {% endif %}
                        </p>
                        <form action="{% url 'authorize' visitor.id %}" method="POST">
                            {% csrf_token %}
                            <button type="submit">Authorize</button>
                        </form>
                        <form action="{% url 'unauthorize' visitor.id %}" method="POST">
                            {% csrf_token %}
                            <button type="submit">Unauthorize</button>
                        </form>
                    </li>
                {% endfor %}
            </ul>
        </div>
    </div>
{% else %}
    <div class="unauthorized">
        <h1>You are not authorized to view this page</h1>
        <a href="{% url 'index' %}">Back to Homepage</a>
    </div>
{% endif %}
</body>
</html>


{% for visitor in visitors %}
<div class="header-1">
  <h1>hello world</h1>
  <p>{{ visitor.user.username }} is  
      {% if visitor.is_authorized %}
          authorized
      {% else %}
          unauthorized now 
          {% endif %}
  </p>
  <div class=" action-button">
      <form action="{% url 'authorize' visitor.id %}" method="POST">
          {% csrf_token %}
          <button type="submit">Approve </button>
       </form>
       <form action="{% url 'unauthorize' visitor.id %}" method="POST">
          {% csrf_token %}
          <button type="submit">Unauthorize</button>
      </form>
     </div>

  </div>
  {% endfor %} 
