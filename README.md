# Firstprojects
My first projects from the SheCodes workshop!

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Homework week 1</title>
    <style>
      h1 {
        color: #1a64d6;
        font-family: Arial, Helvetica, sans-serif;
        text-align: center;
        margin: 0 auto;
        font-size: 34px;
        line-height: 50px;
      }
      h2 {
        text-align: center;
        font-family: Arial, Helvetica, sans-serif;
        font-weight: normal;
        font-size: 32px;
        line-height: 0px;
      }
      ul {
        list-style: none;
        padding: 0;
        text-align: center;
        font-family: Arial, Helvetica, sans-serif;
      }
      li {
        padding: 10px;
        border-radius: 4px;
        margin: 0 auto;
        max-width: 400px;
      }
      li:hover {
        background-color: #fff8ef;
        border-radius: 10px;
        transition: all 300ms ease-in-out;
      }
      .temperature-tomorrow {
        font-size: 18px;
        opacity: 0.7;
        font-family: monospace;
      }
      .temperature-saturday {
        font-size: 18px;
        opacity: 0.7;
        font-family: monospace;
      }
      .temperature-sunday {
        font-size: 18px;
        opacity: 0.7;
        font-family: monospace;
      }
      button {
        display: block;
        margin: 20px auto;
        background-color: #1a64d6;
        color: white;
        border-radius: 30px;
        padding: 16px 24px;
        border: 1px solid #1a64d6;
        border-color: #1a64d6;
        font-size: 16px;
        line-height: 22px;
        box-shadow: 0px 4px rgba(0, 0, 0, 0.09);
      }
      button:hover {
        transition: all 200ms ease-in-out;
        cursor: pointer;
        background-color: white;
        color: #1a64d6;
      }
      .code-designer {
        text-align: center;
        font-family: monospace;
        font-size: 18px;
        opacity: 0.7;
      }
    </style>
  </head>
  <body>
    <h1>
      🌤
      <br />
      Currently 21° in Tokyo
    </h1>
    <h2>
      13°
      <strong>
        / 23°
      </strong>
    </h2>
    <ul>
      <li>
        <h3>
          🌧 Tomorrow
        </h3>
        <p class="temperature-tomorrow">
          10° /
          <strong>22°</strong>
        </p>
      </li>
      <li>
        <h3>🌥 Saturday</h3>
        <p class="temperature-saturday">
          15° /
          <strong>17°</strong>
        </p>
      </li>
      <li>
        <h3>🌞 Sunday</h3>
        <p class="temperature-sunday">
          25° /
          <strong>28°</strong>
        </p>
      </li>
    </ul>
    <button>Change city</button>
    <p class="code-designer">
      Coded by Kayleigh van Es
    </p>
  </body>
</html>
