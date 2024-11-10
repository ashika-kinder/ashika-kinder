<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- displays site properly based on user's device -->

    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./images/favicon-32x32.png"
    />

    <link rel="stylesheet" href="styles/index.css" />

    <title>Frontend Mentor | Interactive rating component</title>

    <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
    <style>
      .attribution {
        font-size: 11px;
        text-align: center;
        color: #fff;
      }
      .attribution a {
        color: hsl(228, 45%, 44%);
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="card">
        <div class="card__image">
          <img src="images/icon-star.svg" alt="star" />
        </div>
        <h1 class="card--title">How did we do?</h1>
        <p class="card--paragraph">
          Please let us know how we did with your support request. All feedback
          is appreciated to help us improve our offering!
        </p>
        <ul>
          <li class="list__item">1</li>
          <li class="list__item">2</li>
          <li class="list__item">3</li>
          <li class="list__item">4</li>
          <li class="list__item">5</li>
        </ul>
        <button class="btn__submit">Submit</button>
      </div>
      <div class="success">
        <div class="success_img">
          <img src="images/illustration-thank-you.svg" alt="thankyou" />
        </div>

        <p class="success__value">
          You selected <span class="span__value">x</span> out of 5
        </p>
        <h1>Thank you!</h1>
        <p class="success__bottom">
          We appreciate you taking the time to give a rating. If you ever need
          more support, don’t hesitate to get in touch!
        </p>
      </div>
    </div>

    <div class="attribution">
      Challenge by
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
        >Frontend Mentor</a
      >. Coded by <a href="#">Kenneth</a>.
    </div>

    <script src="script.js"></script>
  </body>
</html>

