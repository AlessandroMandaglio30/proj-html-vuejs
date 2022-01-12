<template>
  <section id="marketing">
    <div class="primo_cont">
      <div class="sx">
        <img src="../../assets/images/svg/first.svg" alt="Increase" />
      </div>
      <div class="dx">
        <h3>Business Growth</h3>
        <h2>Increase Brand Awareness</h2>
        <h5>
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sed auctor
          placerat luctus. Nullam sit amet ante sed orci covallis gravida et at
          massa.
        </h5>
        <div class="btn btn_orange">Get A Consultation</div>
      </div>
    </div>
    <div class="secondo_cont">
      <div class="sx">
        <h3>Investors In People</h3>
        <h2>In-House Sales Training</h2>
        <h5>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor
          placerat luctus. Nullam sit amet ante sed orci convallis gravida et at
          massa.
        </h5>
        <div class="btn btn_orange">Get A Consultation</div>
      </div>
      <div class="dx">
        <img src="../../assets/images/svg/second.svg" alt="In-House" />
      </div>
    </div>
    <div class="terzo_cont">
      <div class="sx">
        <img src="../../assets/images/svg/third.svg" alt="Increase" />
      </div>
      <div class="dx">
        <h3>Social Media Analysis</h3>
        <h2>Harness Your Social Proof</h2>
        <h5>
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sed auctor
          placerat luctus. Nullam sit amet ante sed orci covallis gravida et at
          massa.
        </h5>
        <div class="btn btn_orange">Get A Consultation</div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Marketing",
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/variables.scss";
.primo_cont {
  display: flex;
  .sx {
    margin-left: 150px;
    img {
      height: 600px;
    }
  }
  .dx {
    width: 20%;
    margin-left: 23%;
    margin-top: 8%;
    h3 {
      font-size: 25px;
      margin-bottom: 20px;
    }
    h2 {
      font-size: 45px;
      margin-bottom: 20px;
    }
    h5 {
      font-size: 23px;
      color: $FlaxSmoke;
    }
    .btn_orange {
      color: $White;
      background-color: $Ectasy;
      margin-top: 20px;
      border-radius: 10px;
      padding: 15px 80px;
      font-size: 15px;
      cursor: pointer;
      display: inline-block;
      &:hover {
        color: $White;
        background-color: $Ectasy;
      }
    }
  }
}
.secondo_cont {
  display: flex;
  .sx {
    width: 20%;
    margin-left: 23%;
    margin-top: 8%;
    h3 {
      font-size: 25px;
      margin-bottom: 20px;
    }
    h2 {
      font-size: 45px;
      margin-bottom: 20px;
    }
    h5 {
      font-size: 23px;
      color: $FlaxSmoke;
    }
    .btn_orange {
      color: $White;
      background-color: $Ectasy;
      margin-top: 20px;
      border-radius: 10px;
      padding: 15px 80px;
      font-size: 15px;
      cursor: pointer;
      display: inline-block;
      &:hover {
        color: $White;
        background-color: $Ectasy;
      }
    }
  }
  .dx {
    margin-left: 180px;
    img {
      height: 600px;
    }
  }
}
.terzo_cont {
  display: flex;
  .sx {
    margin-left: 150px;
    img {
      height: 600px;
    }
  }
  .dx {
    width: 20%;
    margin-left: 23%;
    margin-top: 8%;
    h3 {
      font-size: 25px;
      margin-bottom: 20px;
    }
    h2 {
      font-size: 45px;
      margin-bottom: 20px;
    }
    h5 {
      font-size: 23px;
      color: $FlaxSmoke;
    }
    .btn_orange {
      color: $White;
      background-color: $Ectasy;
      margin-top: 20px;
      border-radius: 10px;
      padding: 15px 80px;
      font-size: 15px;
      cursor: pointer;
      display: inline-block;
      &:hover {
        color: $White;
        background-color: $Ectasy;
      }
    }
  }
}
</style>