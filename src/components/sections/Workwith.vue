<template>
  <section id="workwith">
    <div class="testo">
      <h2>Some Brands We Work With</h2>
      <p>Quisque aliquet, libero consequat elementum convallis.</p>
    </div>
    <div class="img">
      <img src="../../assets/images/abstract.png" alt="abstract" />
      <img src="../../assets/images/cglobal.png" alt="cglobal" />
      <img src="../../assets/images/next.png" alt="next" />
      <img src="../../assets/images/hemisferio.png" alt="hemisferio" />
      <img src="../../assets/images/spaces.png" alt="spaces" />
      <img src="../../assets/images/digitalbox.png" alt="digitalbox" />
    </div>
    <div class="drive">
      <img src="../../assets/images/marketing-expert-cta.png" alt="avatar" />
      <h6>
        Sandy Reiff <br />
        <p>Marketing Consultation Expert</p>
      </h6>
      <h5>Drive Leads ans Sales with Avada</h5>
      <a class="cell" href="#"><i class="fas fa-phone-alt"></i>(555)802-1234</a>
    </div>
  </section>
</template>

<script>
export default {
  name: "Workwith",
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/variables.scss";
#workwith {
  margin-top: 100px;
  text-align: center;
  h2 {
    font-size: 55px;
    margin-bottom: 20px;
  }
  p {
    font-size: 25px;
    color: grey;
  }
  .img {
    margin-top: 55px;
  }
  img {
    margin-left: 70px;
  }
  .drive {
    margin-top: 100px;
    display: flex;
    align-items: center;
    justify-content: space-around;
    border: 0.5px solid rgb(245, 241, 241);
    border-radius: 2px;
    width: 80%;
    height: 80%;
    margin-left: 10%;
  }
  .drive img {
    border-radius: 50%;
    height: 15%;
    width: 4%;
    margin-top: 5px;
  }
  .drive h6 {
    margin-left: -8%;
    font-size: 25px;
    text-align: left;
    margin-right: 10px;
    p {
      font-size: 15px;
    }
  }
  .drive h5 {
    font-size: 35px;
    text-align: left;
  }
  .cell {
    font-size: 1.25rem;
    text-decoration: none;
    color: $Black;
    color: $Ectasy;
    background-color: #ffd2bc;
    border: 1.5px solid $Ectasy;
    margin-left: 0.5rem;
    border-radius: 7px;
    padding: 0.7rem 1.9rem;
    font-size: 1.25rem;
    cursor: pointer;
  }
}
</style>