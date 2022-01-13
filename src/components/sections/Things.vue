<template>
  <section id="things">
    <div class="centro container">
      <div class="sx">
        <h1>Let’s Make Things Happen</h1>
        <h3>
          Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus
          nec ut leo. Integer consectetur.
        </h3>
        <p>
          “The team at Avada Marketing Consultant is fabulous. They helped us
          unlock our potential online and offline. We have experienced year on
          year growth due to their progressive approach.”
        </p>
        <h5>George Anderson</h5>
        <h6>Digitalbox CEO</h6>
      </div>
      <div class="dx">
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
    </div>
  </section>
</template>

<script>
export default {
  name: "Things",
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/variables.scss";
#things {
  background-color: $Black;
  height: 800px;
  .centro {
    display: flex;
  }
  .sx {
    flex: 1;
    color: $White;
    margin-top: 12%;
    h1 {
      font-size: 60px;
    }
    h3 {
      margin-top: 25px;
      font-size: 32px;
    }
    p {
      margin-top: 25px;
      font-size: 27px;
      font-style: italic;
    }
    h5 {
      margin-top: 25px;
      font-size: 25px;
    }
    h6 {
      margin-top: 7px;
      font-size: 15px;
      color: lightgray;
    }
  }
  .dx {
    flex: 1;
    margin-top: 8%;
    margin-left: 12%;
    .riquadro {
      background-color: $White;
      width: 500px;
      height: 650px;
      border-radius: 15px;
      border: 2px solid $GrayNurse;
      text-align: center;
      font-size: 17px;
      .avatar {
        margin-top: 30px;
        border-radius: 50%;
        padding: 7px;
      }
      h4 {
        padding: 12px;
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
        padding: 20px 140px;
        font-size: 17px;
        cursor: pointer;
        display: inline-block;
      }
      p {
        color: $FlaxSmoke;
        margin-top: 12px;
      }
    }
  }
}
</style>