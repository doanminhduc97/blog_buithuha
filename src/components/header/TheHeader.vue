<template>
  <div class="header" id="theHeader">
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
          <li class="icon-heart"><a href="/"></a></li>
        </ul>
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
    .header__navbar {
      display: flex;
      justify-content: space-between;
      height: 100px;
    }
  .logo__img {
    width: 300px;
    height: 76px;
    /* border-radius: 50%; */
  }
  ul {
    display: flex;
  
    li {
      margin: 0 10px;
      font-weight: bold;
      font-size: 14px;
      color: var(--text-color-hover);
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

