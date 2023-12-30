<template>
  <div class="wrapper">

    <!-- Sidebar -->
    <SideNav />

    <div id="right-side">
        <!-- Header -->
        <Header />

        <!-- Main -->
        <Main />
    </div>

  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Projects/Header.vue'
import SideNav from '@/components/Projects/SideNav.vue'
import Main from '@/components/Projects/Main.vue'

export default {
  name: "ProjectView",
  components: {
    Header,
    SideNav,
    Main,
  }
};
</script>

<style lang="less">

/** Scrollbar styling */ 
::-webkit-scrollbar {
  width: 6px;
}

::-webkit-scrollbar-track {
  background: #f1f1f1;
}

::-webkit-scrollbar-thumb {
  background-color: #888;
  border-radius: 6px;
}

::-webkit-scrollbar-thumb:hover {
  background-color: #555;
}

.wrapper {
  display: flex;
  background-color: #eee;
}

#right-side{
  width: 100%;
  padding: 25px;
}

</style>
