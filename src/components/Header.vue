<template>
  <header class="header">
    <div class="container">
      <div class="header-wrapper">
        <div class="header-logo">
          <img src="../assets/images/avada-marketing-logo.png" alt="" />
        </div>
        <div class="header-menu">
          <nav class="header-nav">
            <ul class="list">
              <li class="item" v-for="(link, index) in links" :key="index">
                <a
                  class="link"
                  :class="{ selected: link.selected }"
                  :href="link.link"
                  :title="link.name"
                >
                  {{ link.name }}
                  <div class="freccia">
                    <i class="fas fa-chevron-down"></i>
                  </div>
                  <!-- <div class="apply" v-if="link.apply">Apply</div> -->
                </a>
              </li>
            </ul>
            <a class="cell" href="#"
              ><i class="fas fa-phone-alt"></i>(555)802-1234</a
            >
            <button class="button">Free Quote</button>
          </nav>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      links: [
        {
          name: "Home",
          link: "#",
          selected: true,
        },
        {
          name: "Services",
          link: "#",
          selected: false,
        },
        {
          name: "Why Us",
          link: "#",
          selected: false,
        },
        {
          name: "Case Studies",
          link: "#",
          selected: false,
        },
        {
          name: "About",
          link: "#",
          selected: false,
          apply: true,
        },
        {
          name: "Blog",
          link: "#",
          selected: false,
        },
      ],
    };
  },
};
</script>
<style lang="scss" scoped>
@import "../assets/style/variables.scss";
.header {
  width: 100%;
  position: absolute;
  top: 0;
  &-wrapper {
    display: flex;
    align-items: center;
    height: 90px;
  }
  &-logo {
    height: 40px;
    margin-left: 10%;
    .logo {
      height: 100%;
    }
  }
  &-nav {
    display: flex;
    align-items: center;

    .list {
      display: flex;
      align-items: center;
      .item {
        margin: 0 2.5rem;
        color: $White;
        font-weight: 500;
        font-size: 1.25rem;
        .link {
          display: flex;
          text-decoration: none;
          color: $Black;
        }
      }
    }
    .cell {
      font-size: 1.25rem;
      text-decoration: none;
      margin-right: 0.125rem;
      color: $Black;
    }
    .freccia {
      margin-top: 2px;
      margin-left: 0.125rem;
    }

    .button {
      color: $Ectasy;
      background-color: #f3ba9e;
      border: 1.5px solid $Ectasy;
      margin-left: 0.5rem;
      border-radius: 7px;
      padding: 0.3rem 0.7rem;
      font-size: 1.25rem;
    }
  }
}
</style>