
<html>
  <head>
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1, shrink-to-fit=no"
    />
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/css/bootstrap.min.css"
      integrity="undefined"
      crossorigin="anonymous"
    />
  </head>
  <body>
    <style>
      main {
        display: flex;
        align-items: center;
        justify-items: center;
        align-content: flex-end;
        justify-content: space-around;
        height: 85vh;
      }

      h1 {
        text-transform: uppercase;
        font-size: 0.9em;
        border-bottom: 3px solid #066f06;
        color: #066f06;
        font-weight: bold;
        padding-left: 10px;
        padding-right: 10px;
        padding-bottom: 10px;
        text-align: center;
      }

      .card-attestation {
        padding: 20px;
        background: #08b6e038;
        border-radius: 8px;
      }

      section {
        padding: 30px;
        min-width: 90vw;
      }

      span.small-text-description {
        display: block;
        margin: 10px 0px;
        font-size: 0.7em;
        color: grey;
        text-align: center;
      }

      .title {
        text-transform: uppercase;
        font-weight: bold;
        font-size: 0.8em;
        margin-bottom: 20px;
      }

      .subtitle {
        font-size: 0.6em;
      }

      .content-data {
        font-size: 0.8em;
        text-transform: uppercase;
        font-weight: bold;
      }

      .content {
        /* margin-top: 10px; */
      }

      .content-item {
        margin-top: 10px;
      }

      tr,
      td {
        border: 1px solid;
        padding: 6px 13px;
        font-size: 0.8em;
        font-weight: bold;
      }

      table {
        margin-top: 20px;
      }

      ul.head-align {
        width: 100%;
        display: flex;
        list-style: none;
        align-items: stretch;
        flex-direction: row;
        margin: 0;
        padding: 0;
        justify-content: space-around;
        align-content: stretch;
      }

      ul.head-align li {
        display: flex;
        font-weight: bold;
        font-size: 0.7em;
        text-transform: uppercase;
        color: white;
        max-width: 120px;
        display: block;
        text-align: center;
        align-items: center;
      }

      ul.head-align li img {
        max-width: 51px;
      }

      nav.navbar.navbar-expand-lg.navbar-light.bg-primary {
        background: #066f06 !important;
      }
    </style>
    <nav class="navbar navbar-expand-lg navbar-light bg-primary">
      <ul class="head-align">
        <li>République Gabonaise</li>
        <li class="head-align-image">
          <img
            src="data:image/jpeg;base64,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"
            alt=""
          />
        </li>
        <li>Ministère de la santé</li>
      </ul>
    </nav>

    <main>
      <section>
        <h1>Authentification d'attestation</h1>

        <span class="small-text-description"
          >Le détenteur de cette attestation a été vacciné contre le
          Covid-19</span
        >

        <div class="card-attestation">
          <div class="title">Vaccination contre le Covid-19</div>

          <div class="content">
            <div class="content-item">
              <div class="subtitle">Nom complet</div>
              <div class="content-data">LOUNG NZIENGUI RICKA AIME</div>
            </div>
            <div class="content-item">
              <div class="subtitle">Sexe</div>
              <div class="content-data">M</div>
            </div>
            <div class="content-item">
              <div class="subtitle">Date de naissance</div>
              <div class="content-data">23/01/2001</div>
            </div>
            <div class="content-item">
              <div class="subtitle">ID Unique</div>
              <div class="content-data">COV04-001-01-011406</div>
            </div>
            <table>
              <tr>
                <td>1</td>
                <td>
                  JANSSEN - Lot N°215C21A<br />
                  16/12/2021 - CHR MOUILA
                </td>
              </tr>
            </table>
            <div
              style="display: flex; justify-content: center; margin-top: 20px"
            >
              <img
                src="https://www.vitalsmarts.fr/wp-content/uploads/2020/10/logo-valid%C3%A9.png"
                alt=""
                width="50"
              />
            </div>
          </div>
        </div>
      </section>
    </main>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/js/bootstrap.min.js"></script>
  </body>
</html>
