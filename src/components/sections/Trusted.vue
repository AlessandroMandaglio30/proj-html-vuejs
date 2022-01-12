<template>
  <section id="trusted">
    <h3>Trusted Leading Organisa</h3>
    <div class="img">
      <img src="../../assets/images/case-studies-1.jpg" alt="case-studies1" />
      <img src="../../assets/images/case-studies-4.jpg" alt="case-studies4" />
      <img src="../../assets/images/case-studies-6.jpg" alt="case-studies6" />
    </div>
    <div class="descrizione">
      <h4>
        How Spaces attracted five million visitors by improving the content
        <br />
        <h5 class="due">200%</h5>
        <br />
        <p>Higher revenue from digital</p>
      </h4>
      <h4 class="maschio">
        Creativity helped Hemisferio to increase their brand reach vertically
        <br />
        <h5>10x</h5>
        <br />
        <p>Sales increase with the same ad spend</p>
      </h4>
      <h4>
        How DigitalBox used AI-powered data insight to boost sales
        <br />
        <h5 class="tre">3-year</h5>
        <br />
        <p>Partnership with Avada Consultant</p>
      </h4>
    </div>
    <a class="btn btn_orange" href="#">Read More Case Studies</a>
  </section>
</template>

<script>
export default {
  name: "Trusted",
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/variables.scss";
#trusted {
  margin-top: 120px;
  text-align: center;
  h3 {
    font-size: 50px;
    margin-bottom: 40px;
  }
  .img {
    display: flex;
    margin-left: 13%;

    height: 500px;
  }
  img {
    margin: 20px;
  }
  .descrizione {
    display: flex;
    font-size: 25px;
    width: 60%;
    text-align: left;
    margin-left: 270px;
    .maschio {
      font-size: 23px;
      padding: 0px 201px;
    }
    h5 {
      margin-top: 20px;
      font-size: 50px;
    }
    p {
      margin-top: -17px;
      font-size: 17px;
    }
    .due {
      margin-top: 40px;
    }
    .tre {
      margin-top: 32px;
    }
  }
  .btn {
    margin-top: 80px;
    font-size: 20px;
  }
}
</style>