<script>
  import logo from '../../components/logo.png'
  import aboutImg from '../../components/aboutImg.jpg'
</script>
<main>
  <nav class="navbar navbar-expand-lg text-light navbar-dark" data-bs-theme="dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#top"><img src={logo} alt="" class="logo" /></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
        <ul class="navbar-nav ">
        <li class="nav-item">
            <a href="/" class="nav-link">Home</a>
        </li>
        <li class="nav-item">
          <a href="/about" class="nav-link">About Us</a>
        </li>
        <li>
          <a href="/faq" class="nav-link">Help</a>
        </li>
      </ul>
    </div>  
    </div>
  </nav>
    <section class="section"> 
    <h1 class="first">About</h1>
     <p> Speed test is a measurement of how fast your internet is in real-time. This website tell us the uploading and downloading speed of the internet.</p>
     <img src={aboutImg} alt = "img" class="responsive" />  
     <h6 class="second">About Site<br>
      speed.com is the definitive way to test the speed and performance of your internet connection. Every day, Our commitment to providing transparency into the performance of networks is what drives us. Whether helping our users assess the speed of their individual connections through the Speed test application or publishing analysis, our team is always working to provide data that will help make the internet better and faster for everyone.</h6>
      <footer>
        <a href="#down">
         About us<br>
         Help<br>
         Home<br>
        </a>
      </footer>   
</main>

<style>
  section{
    position: relative;
    background: radial-gradient(41.32% 33.84% at -8.3% 16.18%, rgba(255, 255, 255, 0.2) 0%, rgba(0, 0, 0, 0) 100%) , linear-gradient(135deg, #300046 0%, #030750 59.37%, #340046 81.77%);
    height: 1500px;   
  }  
  .first {
    position: relative;
    top: 100px;
    margin-left: 20px;
    font-family: 'Inika';
    font-weight: 700;
    font-size: 10vw;
    align-items: center;
    color: #00FFFF;
  }
  p {
    position: relative;
    width: 538px;
    top: 100px;
    font-weight: 700;
    font-family: 'Inika';
    font-size: 2.5vw;
    margin-left: 20px;
    align-items: center;
    text-align: left;
    color: #FFFFFF;
  }
  .responsive {
    position: absolute;
    width: 60%;
    height: auto;
    left: 40%;
    top: 50px;
  }  
  .second {
    position: relative;
    top: 350px;
    font-weight: 700;
    font-family: 'Inika';
    font-size: 3vw;
    align-items: center;
    text-align: center;
    color: #FFFFFF;
  }
  footer {
  position: relative;
  width: 100%;
  height: 200px;
  left: 0px;
  top: 410px;
  background: linear-gradient(92.91deg, rgba(0, 178, 255, 0.33) 0%, rgba(4, 7, 79, 0.52) 101.35%); 
  font-family: 'Inika';
  font-style: normal;
  font-weight: 700;
  font-size: 2vw;
  line-height: 31px;
  display: flex;
  align-items: center;
  color: #FFFFFF; 
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
    color: white
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
</style>