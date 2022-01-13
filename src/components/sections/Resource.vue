<template>
  <section id="resource">
    <div class="container">
      <div class="sopra">
        <div class="sx">
          <h3>
            Marketing Resources: Insider Advice on How to Increase Online Sales
          </h3>
        </div>
        <div class="dx">
          <div class="btn_orange">Explore All Resource</div>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="card">
        <img src="../../assets/images/blog-posts-6.jpg" alt="pc" />
        <div class="card-text">
          <div class="desc">
            <h4>Marketing Tips And Tricks For Your Website</h4>
          </div>
        </div>
      </div>
      <div class="card">
        <img src="../../assets/images/blog-posts-5.jpg" alt="Scrivere" />
        <div class="card-text">
          <div class="desc">
            <h4>How to Write Stunning Blog Post Titles</h4>
          </div>
        </div>
      </div>
      <div class="card">
        <img src="../../assets/images/blog-posts-4.jpg" alt="Telefono" />
        <div class="card-text">
          <div class="desc">
            <h4>Techniques to Reduce Facebook Ads Spend</h4>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Resource",
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/variables.scss";
#resource {
  background-color: #fbfbfc;
  .sopra {
    margin-top: 10%;
    display: flex;
    .sx {
      width: 50%;
      font-size: 52px;
    }
    .dx {
      display: flex;
      flex-direction: column;
      justify-content: flex-end;
      margin-left: 28%;
      padding: 25px 5px 10px 0px;
    }
  }
  .row {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    margin: 60px 250px;
    gap: 20px;
  }
  .card {
    display: flex;
    flex-wrap: wrap;
    margin: 0 10px;
  }
  img {
    align-items: center;
    width: 100%;
    height: 250px;
    object-fit: cover;
  }
  .desc {
    font-size: 28px;
    padding: 10px 0;
    line-height: 1.6;
  }
}
</style>