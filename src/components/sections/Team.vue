<template>
  <section id="taem">
    <div class="container">
      <div class="sx">
        <img src="../../assets/images/large-testimonial.jpg" alt="" />
      </div>
      <div class="dx">
        <h4>
          “The team at Avada Marketing Consultant is fabulous. They helped us
          unlock our potential online and offline. We have experienced year on
          year growth due to their progressive approach.”
        </h4>
        <h5>Kate Schadler</h5>
        <p>Marketing Consultant – Abstract</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Team",
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/variables.scss";

.container {
  display: flex;

  img {
    margin-top: 12%;
    width: 600px;
    border-radius: 5px;
  }
  .dx {
    margin-top: 8%;
    width: 50%;
    margin-left: 23%;
    h4 {
      font-size: 35px;
    }
    h5 {
      font-size: 25px;
      margin-top: 50px;
    }
    p {
      font-size: 20px;
      margin-top: 40px;
    }
  }
}
</style>