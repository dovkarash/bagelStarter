<template>
  <div class="home">
    <div class="bagel-wrap">
      <div class="bgl-menu">
        <a href="" class="bgl-logo">
          <img src="../assets/bagelstudio.svg" height="" width=""
        /></a>
        <div class="bgl-menu-space"></div>
        <div class="bgl-menu-links">
          <a href="" class="bgl-close-menu-btn"
            ><img src="../assets/close.svg" height="" width=""
          /></a>
          <a href="" class="bgl-menu-link">Link</a
          ><a href="" class="bgl-menu-link">Link</a
          ><a href="" class="bgl-menu-link">Link</a>
        </div>
        <a href="" class="bgl-menu-btn"
          ><img src="../assets/menu.svg" height="" width=""
        /></a>
      </div>
      <div class="bgl-w560">
        <h1 class="bgl-big-head">Wellcome to<br />Bagel studio</h1>
        <p class="bgl-text">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
          minim veniam, quis nos
        </p>
        <div class="bgl-dropdown open">
          <div class="bgl-dropdown-head">
            <p>Dropddown<br /></p>
            <img
              src="../assets/down.svg"
              height=""
              width=""
              class="bgl-dropdown-arrow"
            />
          </div>
          <div class="bgl-dropdown-content">
            <a href="" class="bg-dropdown-link">Link</a>
            <a href="" class="bg-dropdown-link">Link</a>
            <a href="" class="bg-dropdown-link">Link</a>
          </div>
        </div>
        <div class="bgl-box">
          <p class="bgl-text">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi
            ut&nbsp;
          </p>
        </div>
        <div class="bgl-form">
          <form action="/" class="">
            <label for="" class="bgl-label">label</label
            ><input
              placeholder="Name"
              type="text"
              id=""
              name=""
              class="bgl-input"
            /><label for="" class="bgl-label">label</label
            ><input
              placeholder="Email"
              type="email"
              id=""
              name=""
              class="bgl-input"
            /><label for="" class="bgl-label">label</label
            ><textarea
              placeholder="Message"
              id=""
              name=""
              class="bgl-input"
            ></textarea>
            <div class="bgl-radio-wrap">
              <input
                type="radio"
                id=""
                name="radio"
                value="radio1"
                class="bgl-radio"
              />
              <label for="" class="bgl-radio-label">radio1</label>
            </div>
            <div class="bgl-radio-wrap">
              <input
                type="radio"
                id=""
                name="radio"
                value="radio2"
                checked=""
                class="bgl-radio"
              /><label for="radio2" class="bgl-radio-label">radio2</label>
            </div>



            <div class="bgl-checkbox-wrap">
              <input
                class="bgl-checkbox"
                type="checkbox"
                id="bglcheckbox"
                name="bglcheckbox"
             checked
              />
              <label class="bgl-checkbox-label" for="bglcheckbox">checkbox</label>
            </div>

            <input type="submit" id="" value="Submit" class="bgl-form-btn" />
          </form>
          <div class="bgl-form-success">
            <p>Thank you for getting in touch!</p>
          </div>
          <div class="bgl-form-fail">
            <p>Something went wrong while sending the form</p>
          </div>
        </div>
        <p class="bgl-text">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
          minim veniam, quis&nbsp;
        </p>
        <div class="bgl-tabs">
          <div class="bgl-tabs-head">
            <div class="bgl-tab-head open"><p>Tab 1</p></div>
            <div class="bgl-tab-head"><p>Tab 2</p></div>
            <div class="bgl-tab-head"><p>Tab 3</p></div>
          </div>
          <div class="bgl-tabs-content">
            <div class="bgl-tab open"><p>Text for tab 1</p></div>
            <div class="bgl-tab"><p>Text for tab 2</p></div>
            <div class="bgl-tab"><p>Text for tab 3</p></div>
          </div>
        </div>
        <div class="center">
          <a href="" class="soc-link">
            <img src="../assets/facebook.svg" height="" width="" /></a
          ><a href="" class="soc-link">
            <img src="../assets/linkedin.svg" height="" width="" /></a
          ><a href="" class="soc-link">
            <img src="../assets/twitter.svg" height="" width=""
          /></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>
