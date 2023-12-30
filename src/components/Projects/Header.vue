<template>
   <!-- Top Header -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <i class="fas fa-align-left"></i>
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarScroll" aria-controls="navbarScroll" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarScroll">
        <ul class="navbar-nav me-auto my-2 my-lg-0 navbar-nav-scroll" style="--bs-scroll-height: 100px;">
          <li class="nav-item">
            <a class="nav-link " href="#">
              <form class="d-flex">
                <select name="" id="" class="form-control w-space">
                  <option value="">My Workspace</option>
                </select>
                <button class="btn btn-primary no-border" type="button"><i class="fas fa-arrow-down"></i></button>
              </form>
            </a>
          </li>
          
        </ul>
        <ul class="navbar-nav ms-auto my-2 my-lg-0 navbar-nav-scroll" style="--bs-scroll-height: 100px;">
          <!-- Add ms-auto to align the following list to the right -->
          <li class="nav-item">
            <form class="d-flex">
              <input class="form-control no-border" type="search" placeholder="Search here" aria-label="Search">
              <button class="btn btn-primary no-border" type="button">Search</button>
            </form>
          </li>
          <li class="nav-item m-gap">
            <a class="nav-link" href=""><i class="fas fa-bell"></i></a>
          </li>
          <li class="nav-item m-gap">
            <a class="nav-link" href=""><i class="fas fa-info-circle"></i></a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarScrollingDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Welcome Grace
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarScrollingDropdown">
              <li><a class="dropdown-item" href="#">Profile</a></li>
              <li><hr class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="#">Support</a></li>
              <li><hr class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="#">Settings</a></li>
              <li><hr class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="#">Log Out</a></li>
            </ul>
          </li>
          <li class="nav-item"></li>
        </ul>
      </div>
    </div>
  </nav>

</template>

<script>
export default {
  name: "Header",
  
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
/* Top Header Styles */
.navbar {
  background-color: #fff !important;
  width: 100%;
  border-radius: 5px;

  // border: 1px solid red;
}

.navbar-light .navbar-nav .nav-link {
  color: #495057;
}

.navbar-light .navbar-nav .nav-link:hover {
  color: #007bff;
}

.no-border{
  border-radius: 0px;
}

.m-gap{
  margin: 0px 4px 0px 15px;
}

.w-space{
  width: 220px;
  border-radius: 0px;
}
</style>
