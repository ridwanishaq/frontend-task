<template>
  <nav id="sidebar">
    <div class="sidebar-header">
      <img src="../../assets/wordpilot.png" alt="Sidebar Logo">
    </div>
    <hr>
    <ul class="list-unstyled components">
      <li>
        <a href="#"><i class="fas fa-dashboard"></i> Dashboard</a>
      </li>
      <li class="active">
        <a href="#"><i class="fas fa-folder"></i> Projects</a>
      </li>
      <li>
        <a href="#"><i class="fas fa-calendar"></i> Scheduler</a>
      </li>
      <li>
        <a href="#"><i class="fas fa-magic"></i> Content Wizard</a>
      </li>
      <li>
        <a href="#"><i class="fas fa-file"></i> Documents</a>
      </li>
      <li>
        <a href="#"><i class="fas fa-power-off"></i> Log Out</a>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "SideNav",

};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
#sidebar {
  min-width: 290px;
  max-width: 290px;
  background: #222;
  color: #fff;
  transition: all 0.3s;
  height: 100vh;
  padding: 10px 30px;

  .sidebar-header {
    padding-top: 30px;
    padding-bottom: 18px;
    text-align: center;
  }

  .components {
    margin-top: 40px;
  }

  a {
    padding: 10px;
    text-align: left;
    text-decoration: none;
    font-size: 17px;
    color: #818181;
    display: block;
    transition: color 0.3s;
    border-radius: 6px;

    i {
      padding-right:8px;
    }
  }

  a:hover {
    color: #f1f1f1;
    background: #333;
  }

  .active a {
    color: #fff;
    background: #007bff;
  }

}


</style>
