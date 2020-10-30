<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <script src="https://cdnjs.cloudflare.com/ajax/libs/axios/0.16.1/axios.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/vue/2.3.0/vue.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bulma/0.4.1/css/bulma.min.css">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
  <title>AKON Tank IOT Web Site</title>
</head>
<body>
  <style>
  html, body {
    height: 100%;
    padding: 0;
    margin: 0;
    overflow: hidden;
  }
  #app {
    height: 100%;
    margin: 0;
    padding: 0;
    background-color: #E6E6E6;
  }
  #app .column {
    margin-top: 10%;
  }
  #app .column > p {
    text-align: center;
  }
  #sign-up-button {
    float: right;
  }
</style>

<body>
  <!--main container-->
  <div class="columns is-mobile" id="app">
    <!--centered column-->
    <div class="column is-half is-offset-one-quarter">
      <p class="title is-2 is-spaced">AKON Tank Iot Web Site</p>
      <!--login form-->
      <div class="box">
        <form>
          <div class="field">
            <p class="control has-icons-left">
              <input class="input" type="email" placeholder="Email">
              <span class="icon is-small is-left">
                <i class="fa fa-envelope"></i>
              </span>
            </p>
          </div>
          <div class="field">
            <p class="control has-icons-left">
              <input class="input" type="password" placeholder="Password">
              <span class="icon is-small is-left">
                <i class="fa fa-lock"></i>
              </span>
            </p>
          </div>
          <div class="field">
            <p class="control">

              <button class="button is-success" id="log-in-button">
                Login

              </button>
  <button class="button is-info" id="sign-up-button">

                                      회원가입
                                      </button>

              <hr>
               <a href="www.naver.com"      <hr>도움이 필요하신가요? </a>
                    </button>

            </p>
          </div>
        </form>
      </div>
      <!--end of form-->
    </div>
    <!--end of column-->
  </div>
  <!--end of container-->
</body>
</html>
