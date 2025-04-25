<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/css/bootstrap.min.css" rel="stylesheet">

    <title>HAPPY BIRTHDAY</title>
    <style>
      .t{
        margin-left: 150px;
      }
      button{
        width: 100%;
        max-width: 100%;
        min-height: 120;
      }
      input{
        width: 100%;
        max-width: 100%;
        border-radius: 7px;
      }
      img{
        width: 100%;
        height: 500px;
        max-width: 100%;
        display: block;
        min-height: 300px;
        align-items: center;
      }
      .b{
        color: black;
        background-color: antiquewhite;
      }
      .cl{
        max-width: 100%;
        min-height: 400px;
        width: 100%;
        height: 700px;      
      }
      
    </style>
</head>
<body>
    <h1 class="text-center">HAPPY BIRTHDAY GRANDMA</h1>
    <div id="liveAlertPlaceholder"></div>
<button type="button" class="btn btn-primary col-md-start btn-text-center" id="liveAlertBtn">BRIEF OVERVIEW</button>
<script>
    const alertPlaceholder = document.getElementById('liveAlertPlaceholder')
const appendAlert = (message, type) => {
  const wrapper = document.createElement('div')
  wrapper.innerHTML = [
    `<div class="alert alert-${type} alert-dismissible" role="alert">`,
    `   <div>${message}</div>`,
    '   <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button>',
    '</div>'
  ].join('')

  alertPlaceholder.append(wrapper)
}

const alertTrigger = document.getElementById('liveAlertBtn')
if (alertTrigger) {
  alertTrigger.addEventListener('click', () => {
    appendAlert('Grandma is the prettiest, kindest and best Grandma in the world. Despite the distance, she always takes care of us.She showers us with her love and affection. She is the best Grandma in the whole wide world.', 'primary')
  })
}
</script>

<div>
  <img src="IMG/happy birthday.jpg" alt="birthday image">
</div>


    
    
    


    <div class="accordion accordion-flush" id="accordionFlushExample">
        <div class="accordion-item">
          <h2 class="accordion-header">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
              Why we love her?
            </button>
          </h2>
          <div id="flush-collapseOne" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">Grandma isn't just good, she is the best. We love her because she loves us.</div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
              What we love about her
            </button>
          </h2>
          <div id="flush-collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">We love how you show love, affection, and kindness towards us and everyone around you. She is more than good. She is the best.</div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
              Special message
            </button>
          </h2>
          <div id="flush-collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">Happy birthday to the most selfless, kind-hearted, and loving grandma in the world. We love you more than words can express.</div>
          </div>
        </div>
      </div>

      <div class="b">
      <div class="container-fluid">
        <br>
        <br>
        <br>
      <h2 class="text-center">OUR BIRTHDAY WISHES</h2>

      <p>From Mummy:</p>
      <li>Mummy, mummy, I wish you God's blessings and favor all the days of your life. Igba odun, odun kan ni o.</li>

      <p>From Wisdom:</p>
      <li>I wsh you increase in wisdom, God's protection and guidance. Age gracefully ma.</li>

      <p>From Taiye:</p>
      <li>Happy birthday Grandma. I wish you more joyous years ahead and for God's kindness and protection all the days of your life.</li>

      <p>From Kehinde:</p>
      <li>On this special day of yours, i wish you good health and divine prosperities.you shall live long to celeberate more birthdays.HIP HIP HOORAY!!!  </li>

      <p>From Boluwatife:</p>
      <li>Happy birthday ma. I wish you long life and prosperity. Amen.</li>

      <p>From Emmanuel:</p>
      <li>Happy birthday Grandma.</li>
    </div>
  </div>




  <div id="carouselExampleSlidesOnly" class="carousel slide carouselslide" data-bs-ride="carousel">
    <div class="carousel-inner mt-200 cl">
      <div class="carousel-item active">
        <img src="IMG/IMG-20241016-WA0002.jpg" class="d-block w-100" alt="image">
      </div>
      <div class="carousel-item">
        <img src="IMG/IMG-20241016-WA0003.jpg" class="d-block w-100" alt="image">
      </div>
      <div class="carousel-item">
        <img src="IMG/IMG-20241016-WA0004.jpg" class="d-block w-100" alt="image">
      </div>
      <div class="carousel-item">
        <img src="IMG/IMG-20241016-WA0005.jpg" class="d-block w-100" alt="image">
      </div>
      <div class="carousel-item">
        <img src="IMG/IMG-20241016-WA0006.jpg" class="d-block w-100" alt="image">
      </div>
      <div class="carousel-item">
        <img src="IMG/IMG-20241016-WA0007.jpg" class="d-block w-100" alt="image">
      </div>
      <div class="carousel-item">
        <img src="IMG/IMG-20241016-WA0008.jpg" class="d-block w-100" alt="image">
      </div>
      <div class="carousel-item">
        <img src="IMG/IMG-20241016-WA0009.jpg" class="d-block w-100" alt="image">
      </div>
      <div class="carousel-item">
        <img src="IMG/IMG-20241016-WA0010.jpg" class="d-block w-100" alt="image">
      </div>
      <div class="carousel-item">
        <img src="IMG/IMG-20241016-WA0011.jpg" class="d-block w-100" alt="image">
      </div>
      <div class="carousel-item">
        <img src="IMG/IMG-20241016-WA0012.jpg" class="d-block w-100" alt="image">
      </div>
      <div class="carousel-item">
        <img src="IMG/IMG-20241016-WA0013.jpg" class="d-block w-100" alt="image">
      </div>
      <div class="carousel-item">
        <img src="IMG/IMG-20241016-WA0014.jpg" class="d-block w-100" alt="image">
      </div>
      <div class="carousel-item">
        <img src="IMG/IMG-20241016-WA0015.jpg" class="d-block w-100" alt="image">
      </div>
    
    </div>
  </div>

  <div class="container-sm">
    <h3 class="text-center">OUR PRAYERS</h3>
    <p class="text-center">We pray that at you celebrate more glorious years ahead. 
      <br>
    There shall always be joy wherever you go.
    <br/>
     You shall live to see your great-grandkids and more ahead. 
    <br />
    Wherever you go, goodness and blessings shall follow.You shall not meet any misfortunes. 
    <br/>
    The Lord's goodness and mercies shall not cease in your life.
    <br>
    IN JESUS NAME. AMEN</p>
  </div>
    
    

    <!-- Modal structure -->
<div id="modal" class="modal" style="display:none;">
  <div class="modal-content">
    <span class="close">&times;</span>
    <p id="modal-message">Happy Birthday, Grandma! Thanks for all the love you have shown to us throughout the years. We love you so much.</p>
  </div>
</div>

<!-- Password input field and submit button -->
<input id="password" type="password" placeholder="Enter password">
<button onclick="checkPassword()" class="btn btn-primary">Submit</button>

<script>
const password = "2504"; // set the password
const modal = document.getElementById("modal");
const modalMessage = document.getElementById("modal-message");
const closeButton = document.getElementsByClassName("close")[0];

function checkPassword() {
  const inputPassword = document.getElementById("password").value;
  if (inputPassword === password) {
    modalMessage.innerText = "Happy Birthday, Grandma! Thanks for all the love you have shown to us throughout the years. We love you so much.";
    modal.style.display = "block";
  } else {
    alert("Incorrect password!");
  }
}

// Close the modal when the close button is clicked
closeButton.onclick = function() {
  modal.style.display = "none";
}

// Close the modal when the user clicks outside of it
window.onclick = function(event) {
  if (event.target == modal) {
    modal.style.display = "none";
  }
}
</script>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
