<template>
  <div class="header" id="theHeader">
    <div class="grid">
      <div class="header__navbar">
        <div class="logo">
          <a href="/">
            <img class="logo__img" src="../../assets/logo2.jpg" alt="">
          </a>
        </div>
        <div class="user-controls">
          <ul class="user-controls__list">
            <li>LOG IN</li>
            <li class="divider">/</li>
            <li>SIGN UP</li>
            <li class="icon-heart">
              <!-- <font-awesome-icon icon="fa-solid fa-user-secret" /> -->
              <!-- <font-awesome-icon size="4" icon="fa-regular fa-heart" /> -->
              <a  href="/"></a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TheHeader',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
#theHeader {
  .logo__img {
    width: 300px;
    height: 76px;
    /* border-radius: 50%; */
  }
  ul {
    display: flex;
    list-style-type: none;
  
    li {
      margin: 0 10px;
      font-weight: bold;
      font-size: 14px;
      color: #009ada;
      a {
        height: 24px;
        width: 24px;
        display: inline-block;
        color: #000;
        background: url('../../assets/heart.svg') no-repeat;
        &:hover {
          background: url('../../assets/heart-hover.svg') no-repeat;
        }
      }
    }
    .divider {
      color: #d0d0d0;
    }
  }
}



// .divider {

// }

</style>

