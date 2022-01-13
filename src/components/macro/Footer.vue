<template>
  <footer>
    <nav class="container">
      <div class="content">
        <div class="scritta">
          <h4>
            Grow Your Online Business Strategically, and Improve Customer
            Retention.
          </h4>
          <div class="social">
            <a href="#"><i class="fab fa-facebook-square"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
            <a href="#"><i class="fab fa-youtube"></i></a>
            <a href="#"><i class="fab fa-linkedin"></i></a>
            <a href="#"><i class="fab fa-tiktok"></i></a>
          </div>
        </div>
        <ul class="link">
          <h4>Services</h4>
          <li><a href="#">Marketing Plan</a></li>
          <li><a href="#">Sales Development</a></li>
          <li><a href="#">Digital</a></li>
          <li><a href="#">Pricing</a></li>
          <li><a href="#">Why Us</a></li>
          <li><a href="#">Case Studies</a></li>
        </ul>
        <ul class="link">
          <h4>Resources</h4>
          <li><a href="#">Learning Center</a></li>
          <li><a href="#">Video Tutorials</a></li>
          <li><a href="#">Customers</a></li>
          <li><a class="sot" href="#">Blog</a></li>
        </ul>
        <ul class="link">
          <h4>Company</h4>
          <li><a href="#">Who We Are</a></li>
          <li><a href="#"> Contact Us</a></li>
          <li><a href="#">Careers</a></li>
        </ul>
      </div>
      <div class="sotto">
        <a href="#">© 2020 • Avada Consultant • Powered by WordPress</a>
        <a class="call" href="#">Call Us (555)802-1234</a>
        <a href="#">info@yourcompany.com</a>
      </div>
      <div>
        <div class="riquadro">
          <img
            class="avatar"
            src="../../assets/images/marketing-expert-cta.png"
            alt=""
          />
          <p>
            This is a free HubSpot live chat. You can create your own chat flows
            and engage your customers with Avada & HubSpot!
          </p>
        </div>
        <i class="chat fas fa-comments"></i>
      </div>
    </nav>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/variables.scss";
footer {
  height: 570px;
  margin-top: 5%;
  .content {
    display: flex;
    .scritta {
      width: 30%;
      font-size: 34px;
    }
    .social {
      margin-top: 30px;
      a {
        margin: 10px;
      }
    }
    .link {
      margin-left: 15%;
      h4 {
        font-size: 25px;
      }
      li {
        margin-top: 15px;
        font-size: 20px;
      }
    }
  }
  .sotto {
    display: flex;
    justify-content: space-between;
    margin-top: 5%;
    font-size: 18px;
    .call {
      margin-left: -20%;
    }
  }
  .riquadro {
    background-color: $White;
    width: 230px;
    height: 140px;
    margin-left: 102%;
    margin-top: -5%;
    border-radius: 5px;
    border: 2px solid $GrayNurse;
    text-align: center;
    font-size: 16px;
    .avatar {
      margin-top: -40px;
      border-radius: 50%;
      padding: 7px;
      height: 80px;
      width: 80px;
    }
  }
  .chat {
    color: $Tango;
    margin-left: 114%;
    font-size: 45px;
    margin-top: 20px;
  }
}
</style>