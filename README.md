<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Overpass:ital,wght@0,100..900;1,100..900&display=swap"
    rel="stylesheet">
  <link rel="stylesheet" href="style.css">
  <title>How Did We Do?</title>
</head>

<body>
  <section id="rating-component">
    <div class="component-content">
      <div class="star-img">
        <img src="./images/icon-star.svg" alt="star icon">
      </div>
      <h2>How did we do?</h2>
      <p>
        Please let us know how we did with your support request. All feedback
        is appreciated to help us improve our offering!
      </p>
      <form>
        <ul class="rating-numbers">
          <li class="rating-number">
            <button id="1-rating" class="rating-btn" type="button">1</button>
          </li>
          <li class="rating-number m-left">
            <button id="2-rating" class="rating-btn" type="button">2</button>
          </li>
          <li class="rating-number m-left">
            <button id="3-rating" class="rating-btn" type="button">3</button>
          </li>
          <li class="rating-number m-left">
            <button id="4-rating" class="rating-btn" type="button">4</button>
          </li>
          <li class="rating-number m-left">
            <button id="5-rating" class="rating-btn" type="button">5</button>
          </li>
        </ul>
        <div class="sumbmit-container">
          <input id="submit-btn" value="SUBMIT" type="submit">
        </div>
      </form>
    </div>
  </section>

  <section id="thankyou-component">
    <div class="thankyou-img">
      <img src="./images/illustration-thank-you.svg" alt="thank you img">
    </div>
    <p id="dynamic-text">You selected <span class="dynamic-number"></span>out of 5
    </p>
    <h2 class="thankyou-heading">
      Thank you!
    </h2>
    <p class="thankyou-text">
      We appreciate you taking the time to give a rating. If you ever need
      more support, don’t hesitate to get in touch!
    </p>
  </section>
  <script src="script.js"></script>
</body>

</html>

