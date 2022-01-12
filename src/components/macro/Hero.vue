<template>
  <div class="hero">
    <!-- testo a destra del jumbotron -->
    <div class="text-hero">
      <div class="subtitle">
        <h1>
          Your Online <br />
          Growth Potential
        </h1>
      </div>
      <div class="title"></div>
      <h5>
        Online marketing to secure costomer retention, leads, and sales. We
        focus on the bigger picture
      </h5>
      <div class="btn btn_white">
        Our Services
        <i class="fas fa-long-arrow-alt-right"></i>
      </div>
    </div>
    <!-- scritte laterali -->
    <div class="riquadro">
      <img
        class="avatar"
        src="../../assets/images/marketing-consultant-expert.jpg"
        alt="Avatar"
      />
      <h3>Ricahrd Madsen</h3>
      <h4>Marketing Consultant Expert</h4>
      <h4 class="colore"><i class="fas fa-phone-alt"></i>(555)802-1234</h4>
      <input type="text" id="nome" placeholder="Your Name*" />
      <input type="text" id="email" placeholder="Your Email*" />
      <input type="tel" id="numero" placeholder="Your Phone Number*" />
      <div class="btn btn_orange">Get A Callback</div>
      <p>By submitting my data i agree to be contacted</p>
    </div>
  </div>
</template>

<script>
export default {
  nome: "Hero",
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/variables.scss";

.hero {
  height: 800px;
  background-image: url("../../assets/images/marketing-intro.jpg");
  background-position: center;
  background-size: cover;
  display: flex;

  .text-hero {
    color: $White;
    text-align: left;
    position: relative;
    width: 25%;
    top: 40%;
    left: 10%;
    .subtitle {
      font-size: 1.75rem;
      font-weight: bold;
    }
    h5 {
      font-size: 1.2rem;
      font-weight: 100;
      margin: 5px 0 30px 0;
    }
    .btn_white {
      color: $Black;
      background-color: #fff;
      border-radius: 10px;
      padding: 20px 30px;
      cursor: pointer;
      display: inline-block;
      &:hover {
        color: #fff;
        background-color: $White;
      }
    }
  }
  .riquadro {
    background-color: $White;
    width: 500px;
    height: 550px;
    position: absolute;
    top: 30%;
    left: 50%;
    border-radius: 15px;
    border: 2px solid $GrayNurse;
    text-align: center;
    font-size: 17px;
    .avatar {
      border-radius: 50%;
      padding: 7px;
    }
    h4 {
      padding: 7px;
      color: $Gunsmoke;
    }
    .colore {
      color: $Ectasy;
    }
    input {
      display: flex;
      width: 80%;
      border-radius: 3px;
      border: 1px solid $GrayNurse;
      padding: 10px;
      margin-top: 10px;
      font-size: 17px;
      margin-left: 50px;
    }
    .btn_orange {
      color: $White;
      background-color: $Ectasy;
      margin-top: 20px;
      border-radius: 10px;
      padding: 20px 140px;
      font-size: 17px;
      cursor: pointer;
      display: inline-block;
      &:hover {
        color: #fff;
        background-color: $Ectasy;
      }
    }
    p {
      color: $FlaxSmoke;
      margin-top: 12px;
    }
  }
}
</style>