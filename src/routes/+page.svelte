<script>
  import logo from '../components/logo.png'
</script>
<body>
    
    <main>
        <nav class="navbar navbar-expand-lg text-light navbar-dark" data-bs-theme="dark">
            <div class="container-fluid">
              <a class="navbar-brand" href="#"><img src={logo} class="logo"/></a>
              <button class="navbar-toggler dropdown" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
                <ul class="navbar-nav">
                <li class="nav-item">
                    <a href="/" class="nav-link ">Home</a>
                </li>
                <li class="nav-item">
                  <a href="about" class="nav-link ">About Us</a>
                </li>
                <li>
                  <a href="/faq" class="nav-link ">Help</a>
                </li>
              </ul>
            </div>
            </div>
          </nav> 
          <div class="container">
            <div style="text-align:right;"></div>
                <div style="min-height:360px;">
                    <div class="container2">
                        <div id="check">Check your internet speed..</div>
                        <iframe id="x" src="//openspeedtest.com/speedtest" />
                        <div id="check3">
                            <input type="button" id="check2" value="Retry test" onclick="location.reload();">
                        </div>
                    </div>
                </div>
            </div>   
    </main>
</body>
    <style>
        body{
            background:linear-gradient(55deg,rgb(67, 0, 121),rgb(0, 4, 63),rgb(0, 0, 99));
            background-attachment:fixed ;
        }
        img{
    background-color: white;
  }
  ul {
    margin: 14px 3px;
    padding: 3px 17px;
    color: aliceblue;
    size: 44pt;
  }
  a {
    color: white;
  }
  li a{
    border-radius: 5px;
  }
  li a:hover{
    background-color: orange;
    color: black; 
    border-radius: 5px;

  }
  nav {
    background-color: #060c59;
  }

  .logo {
    height: 3rem;
    width: 7rem;
  }
  
  .container {
        display: inline-block;
        background: linear-gradient(
            45deg,
            rgb(0, 0, 194),
            rgba(255, 0, 85, 0.452)
        );
        border-radius: 20px;
        text-align: center;
        padding: 5vh;
        font-size: 30px;
        align-items: center;
        height: 70vh;
        width: 32ch;
        top: 45%;
        left: 50%;
        position: absolute;
        margin-top: -200px;
        margin-left: -250px;
    }
    .container2 {
        display: inline-block;
        background: linear-gradient(
            45deg,
            rgb(0, 0, 194),
            rgba(255, 0, 85, 0.452)
        );
        border-radius: 20px;
        text-align: center;
        padding: 5vh;
        font-size: 30px;
        align-items: center;
        color: #ffffff;
        height: 70vh;
        width: 32ch;
        top: 46%;
        left: 45%;
        position: absolute;
        margin-top: -200px;
        margin-left: -250px;
    }
    #x {
        border: none;
        margin-top: 9px;
        border-radius: 25px;
        width: 90%;
        height: 90%;
        border: none;
        background-color: transparent;
    }
    #check{
        border:bold black 1px;
        border-radius: 9px;
    }
    #check2{
        margin-top: 20px;
        border: 0px;
        padding-right: 3ch;
        padding-left: 3ch;
        border-radius: 15px;
        color: white;
        background: linear-gradient(
            45deg,
            rgb(0, 81, 255),rgb(212, 0, 255)
        );
        padding-top: 3px;
        padding-bottom: 3px;
        font-size: 27px;
    }
    </style>


