<script>
export default {
  name: "FooterComp",
};
</script>

<template>
  <div class="background">
    <div class="container py-5">
      <div class="row">
        <div class="col-6">
          <h5>Address</h5>
          <address>
            <p>382 NE 191st St #87394 Miami, FL 33179-3899</p>
            <p>+1 (305) 547-9909 (9am - 5pm EST, Monday - Friday)</p>
            <p><a href="#">support@maxcoach.com</a></p>
          </address>
          <div class="social-link fs-3">
            <font-awesome-icon
              class="icon"
              icon="fa-brands fa-square-facebook " />
            <font-awesome-icon class="icon" icon="fa-brands fa-twitter" />
            <font-awesome-icon class="icon" icon="fa-brands fa-instagram" />
            <font-awesome-icon class="icon" icon="fa-brands fa-linkedin" />
          </div>
        </div>
        <div class="col-3 d-flex">
          <div class="col-6">
            <ul>
              <h5>Explore</h5>
              <li>Start here</li>
              <li>Blog</li>
              <li>About us</li>
            </ul>
          </div>
          <div class="col-6 mt-2">
            <ul>
              <br />
              <li>Success story</li>
              <li>Courses</li>
              <li>Contact us</li>
            </ul>
          </div>
        </div>
        <div class="col-3">
          <ul>
            <h5>Information</h5>
            <li>Membership</li>
            <li>Purchase guide</li>
            <li>Privacy policy</li>
            <li>Terms of service</li>
          </ul>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-12 pb-5 text-center">
        <span>&copy; 2020 Maxcoach. All Rights Reserved</span>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
@use "../assets/styles/partials/variables" as *;

.background {
  background-color: $cinder;
  color: $silver-sand;

  .social-link .icon {
    padding-right: 2rem;
    color: grey;

    &:hover {
      color: $white;
    }
  }

  address p {
    line-height: 2.5rem;
    margin: 0;
  }

  address a {
    text-decoration: none;
    color: grey;

    &:hover {
      color: white;
    }
  }

  h5 {
    color: $white;
  }

  ul {
    list-style-type: none;

    li {
      line-height: 2.5rem;

      &:hover {
        color: white;
      }
    }
  }
}
</style>
