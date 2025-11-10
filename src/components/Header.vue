<template>
  <div class="header">
    <div class="nav-bar">
      <router-link class="brand" to="/">
        <img src="/Icon.png" alt="Manish Savaliya Logo" class="brand-mark" />
        <span class="brand-text">Manish Savaliya</span>
      </router-link>
      <router-link to="/">About me</router-link>
      <router-link to="/game-projects">Games</router-link>
      <router-link to="/other-projects">Other Projects</router-link>      
      <router-link to="/contact">Contact</router-link>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "AppHeader"
});

</script>

<style scoped lang="less">

@import '../css/variables.less';

.header {
  width: 100%;
  position: sticky;
  top: 0;
  z-index: 9;
  backdrop-filter:saturate(100%) blur(10px);
}

.nav-bar {
  text-align: right;
  padding: 20px;
  line-height: 3em;
  box-shadow: 0 2px 0 rgba(255,255,255,0.04);
}

a {
  text-transform: uppercase;
  margin-left: 15px;
  margin-right: 15px;
  padding-bottom: 8px;
  white-space: nowrap;
  display: inline-block;
  text-decoration: none;
}

.brand {
  float: left;
  display: inline-flex;
  align-items: center;
  gap: 10px;
  text-transform: none;
  letter-spacing: 0.4px;
  margin-left: 0;
  margin-right: 20px;
  padding-bottom: 0;
}

.brand-mark {
  width: 34px;
  height: 34px;
  border-radius: 9px;
  display: inline-block;
  object-fit: contain;
  flex-shrink: 0;
}

.brand-text {
  font-weight: 800;
  font-size: 1.2em;
  background: linear-gradient(90deg, #ffffff, #c7d2fe);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  text-shadow: 0 0 18px rgba(99,102,241,0.12);
  transition: filter 0.2s ease;
}

/* Keep the brand always bright on all routes; disable hover/active changes */
.brand { opacity: 1 !important; }
.brand:hover { opacity: 1 !important; }
.brand { filter: brightness(1.15) !important; }
.brand .brand-text { filter: brightness(1.15) !important; }
.brand:hover .brand-text { filter: brightness(1.15) !important; }
.brand.router-link-active,
.brand.router-link-exact-active { filter: brightness(1.15) !important; }

.router-link-exact-active {
  border: 0;
  filter: brightness(1.15);
}

@media only screen and (max-width: 620px){
  .nav-bar {
    line-height: 2em;
  }

  a {
    margin-left: 9px;
    margin-right: 9px;
    padding-bottom: 0px;
  }
}

</style>