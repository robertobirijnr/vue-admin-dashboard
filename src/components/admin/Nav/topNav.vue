<template>
  <div class="row">
    <div class="col-md-12 d-flex justify-content-between top-nav-bar">
      <div class="main">
        <div class="form-group has-search">
          <span
            class="iconify form-control-feedback"
            data-icon="ri:search-fill"
            data-inline="false"
          ></span>
          <input type="text" class="form-control" placeholder="Search" />
        </div>
      </div>

      <div class="left-side">
        <span
          class="iconify mr-5"
          data-icon="clarity:notification-solid-badged"
          data-inline="false"
        ></span>
        <img src="@/assets/img_avatar.png" alt="Avatar" class="avatar mr-2" />
        <span>Robert Obiri Jnr</span
        ><span
          class="iconify icondrop dropdown-toggle"
          id="dropdownMenuButton"
          data-toggle="dropdown"
          data-icon="ion:md-arrow-dropdown"
          data-inline="false"
        ></span>
        <div class="dropdown-menu mt-3" aria-labelledby="dropdownMenuButton">
          <a class="dropdown-item" href="#">Profile</a>
          <a class="dropdown-item" href="#">Settings</a>
          <a class="dropdown-item" href="#">Logout</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style  scoped>
.top-nav-bar {
  height: 13vh;
}

.icondrop {
  color: #7c7c7c;
}

.avatar {
  vertical-align: middle;
  width: 50px;
  height: 50px;
  border-radius: 50%;
}

.left-side {
  margin-top: 10px;
}

.main {
  width: 50%;
  margin-top: 20px;
  margin-left: 200px;
}

/* Bootstrap 4 text input with search icon */

.has-search .form-control {
  padding-left: 2.375rem;
}

.has-search .form-control-feedback {
  position: absolute;
  z-index: 2;
  display: block;
  width: 2.375rem;
  height: 2rem;
  line-height: 2.375rem;
  text-align: center;
  pointer-events: none;
  color: #bdbdbd;
  padding-top: 4px;
  font-family: Questrial;
  font-size: 18px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
}

input {
  border-radius: 10px;
}

input:focus {
  box-shadow: none;
  outline: none;
}
</style>