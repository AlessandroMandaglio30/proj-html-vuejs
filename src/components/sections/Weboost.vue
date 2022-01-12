<template>
  <section id="weboost">
    <div class="alta">
      <div class="sx">
        <h3>
          We Boost Our Clients’ Bottom Line by Optimizing Their Growth
          Potential.
        </h3>
        <h4>
          Quisque aliquet, libero consequat elementum convallis, erat risus
          imperdiet pellentesque sem neque eget.
        </h4>
        <a class="btn btn_orange" href="#">Why Work With Us</a>
      </div>
      <div class="dx">
        <img src="../../assets/images/we-boost-our-clients.jpg" alt="" />
      </div>
    </div>
    <div class="centro container">
      <div class="sx">
        <div class="content">
          <h5>We Build Relationships</h5>
          <p>
            Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus
            nec ut leo. Integer consectetur.
          </p>
          <h5>Proprietary Processes</h5>
          <p>
            Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus
            nec ut leo. Integer consectetur.
          </p>
        </div>
      </div>
      <div class="dx">
        <div class="content">
          <div class="accountability row">
            <div class="icon"><i class="fas fa-search"></i></div>
            <div class="text">
              <h5>Accountabiliy</h5>
              <p>Curabitur ac leo nunc vestibulum</p>
            </div>
          </div>
          <div class="transparency row">
            <div class="icon"><i class="fas fa-plus-square"></i></div>
            <div class="text">
              <h5>Transparency</h5>
              <p>Curabitur ac leo nunc vestibulum</p>
            </div>
          </div>
          <div class="investment row">
            <div class="icon"><i class="fas fa-signal"></i></div>
            <div class="text">
              <h5>Investment</h5>
              <p>Curabitur ac leo nunc vestibulum</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="sotto">
      <div class="testo">
        <h2>Awards</h2>
      </div>
      <div class="img">
        <img src="../../assets/images/award-a.png" alt="award" />
        <div class="text">
          <h6>
            Winner Seo Master MAGT <br />
            Smart Start Award 2017
          </h6>
        </div>
        <img src="../../assets/images/award-b.png" alt="award" />
        <div class="text">
          <h6>
            Top Social Media Agencies <br />
            Next Partner 2018
          </h6>
        </div>
        <img src="../../assets/images/award-c.png" alt="award" />
        <div class="text">
          <h6>
            10 Fastest Growing Abstract <br />
            Solution Providers 2019
          </h6>
        </div>
        <img src="../../assets/images/award-d.png" alt="award" />
        <div class="text">
          <h6>
            National Excellence Agencie <br />
            Award Winner 2020
          </h6>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Weboost",
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/variables.scss";
#weboost {
  margin-top: 120px;
  background-color: #fcfcfd;
  height: 100%;
  .alta {
    display: flex;
    .sx {
      width: 20%;
      margin-left: 15%;
      margin-top: 8%;
      h3 {
        font-size: 40px;
        margin-bottom: 20px;
      }
      h4 {
        font-size: 20px;
        margin-bottom: 20px;
      }
    }
    .dx {
      margin-top: 70px;
      margin-left: 150px;
      img {
        height: 600px;
      }
    }
  }
  .centro {
    display: flex;

    .content {
      max-width: 80%;
    }
    .sx {
      flex: 1;

      //   margin-left: 20%;
      margin-top: 8%;
      h5 {
        font-size: 35px;
        margin-bottom: 20px;
      }
      p {
        font-size: 20px;
        margin-bottom: 20px;
      }
    }
    .dx {
      flex: 1;
      margin-top: 8%;
      //   margin-left: 250px;
      .row {
        display: flex;

        margin-bottom: 55px;

        .text {
          display: flex;
          flex-direction: column;
          justify-content: space-between;
          h5 {
            font-size: 22px;
          }
          p {
            font-size: 18px;
          }
        }
        .icon {
          flex-shrink: 0;
          display: flex;
          align-items: center;
          justify-content: center;
          height: 65px;
          width: 65px;
          color: $Tango;
          border: 2px solid $Tango;
          border-radius: 20px;
          margin-right: 15px;
          font-size: 25px;
        }
      }
    }
  }
  .sotto {
    margin-top: 100px;
    text-align: center;
    h2 {
      font-size: 35px;
    }
    .img {
      display: flex;
      justify-content: center;

      .text {
        display: flex;
        flex-direction: column;
        justify-content: end;
        margin-left: -400px;
        padding: 10px;
        font-size: 30px;
      }
      img {
        width: 280px;
        margin: 35px 140px;
      }
    }
  }
}
</style>