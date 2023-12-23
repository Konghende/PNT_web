<template>
  <nav class="flex-container">
    <div class="links">
      <ul class="nav p-0">
        <li class="nav-item">
          <a class="nav-link" href="#">SOFTWARE DESIGN</a>
          <div class="submenu">
            <ul>
              <li><a href="#">Web Development</a></li>
              <li><a href="#">Mobile App Development</a></li>
              <li><a href="#">PGI/ERP Installation</a></li>
            </ul>
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">GRAPHICS DESIGN</a>
          <div class="submenu">
            <ul>
              <li><a href="#">Logo Design</a></li>
              <li><a href="#">Brand Identity Design</a></li>
              <li><a href="#">3D/Motion Design</a></li>
            </ul>
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">IT MAINTENANCE & MONITORING</a>
          <div class="submenu">
            <ul>
              <li><a href="#">Network installation and admininistration</a></li>
              <li><a href="#">Security camara installation</a></li>
            </ul>
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">PNTEC ACADEMY</a>
          <div class="submenu">
            <ul>
              <li><a href="#">Intra-Company training</a></li>
              <li><a href="#">Pedagogical training</a></li>
            </ul>
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">PRODUCTS</a>
          <div class="submenu">
            <ul>
              <li><a href="#">SMSNGIN</a></li>
              <li><a href="#">Refraiche!</a></li>
              <li><a href="#">PNBooking</a></li>
            </ul>
          </div>
        </li>
      </ul>
    </div>
  </nav>
</template>

<style lang="scss" scoped>
.nav {
  background-color: #316670;
  flex-wrap: nowrap;
  align-items: baseline;

  @include media-breakpoint-down(md) {
    overflow: auto;
    white-space: nowrap;
  }
}
.nav-link {
  color: white;
  font-size: 16px;
  text-transform: uppercase;
  text-align: center;
  cursor: pointer;
  padding: 23px 24px;
  font-weight: 500;

  @include media-breakpoint-down(md) {
    padding: 23px 61px;
  }
}
.submenu {
  display: none;
}
ul {
  list-style: none;
  text-align: start;
  padding: 35px 15px;
}
a {
  color: #cfcfcfd7;
  font-size: 1rem;
  text-decoration: none;
}

.links ul li:hover .submenu {
  background-color: #316670;
  display: block;
  position: absolute;
  margin-bottom: 8px;
  width: 100%;
  overflow: none;
}
.nav-item {
  position: relative;
  flex: auto;

  &:not(:last-child) {
    border-right: 1px solid #979696d7;
  }
}
</style>
