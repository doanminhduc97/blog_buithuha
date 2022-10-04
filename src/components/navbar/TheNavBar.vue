<template>
  <div class="theNavBar" id="theNavBar">
    <div class="subcribe">
      <a href="#"> 
        SUBCRIPE
        <font-awesome-icon icon="fa-solid fa-chevron-right" />
      </a>
    </div>
    <div class="navbar-list">
      <ul>
        <li>RECIPES</li>
        <li>EAT OUT</li>
        <li>TRAVEL</li>
        <li>DRINKS</li>
        <li>ENTERTAINING</li>
        <li>FOOD NEWS</li>
        <li>DELICIOUS 100</li>
      </ul>
    </div>
    <div class="search">
      <a href="#">
        SEARCH
        <font-awesome-icon icon="fa-solid fa-magnifying-glass" />
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "TheNavBar",
  data() {
    return {};
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
#theNavBar {
  height: 48px;
  font-size: 16px;
  display: flex;
  justify-content: space-between;
  // align-items: center;
  margin-top: 30px;
  // padding-bottom: 10px;
  padding-left: 12px;
  padding-right: 12px;
  height: 100%;
  .subcribe {
    margin-top: 1px;
    padding-bottom: 10px;
    a {
      color: rgb(218, 218, 218);
      &:hover {
        color: var(--text-color-hover);
      }
    }
  }

  .navbar-list {
    ul {
      display: flex;
      margin: 0;
      padding: 0;
      margin-top: 3px;
      li {
        padding-bottom: 7px;
        margin: 0 10px;
        cursor: pointer;
        font-weight: 600;
        color: var(--text-color);
        border-bottom: 3px solid transparent;
        &:hover {
          border-bottom: 3px solid #000;
        } 
      }
    }
  }

  .search {
    padding-bottom: 9px;
    font-weight: 600;
    a {
      color: var(--text-color);
      &:hover {
        color: var(--text-color-hover);
      } 
    }
  }
}
</style>

