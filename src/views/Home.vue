<template>
  <div class="home">
    <div class="bagel-wrap">
      <div class="bgl-menu">
        <a
            href=""
            class="bgl-logo"
        >
          <img
              src="../assets/bagelstudio.svg"
              height=""
              width=""
           /></a>
        <div class="bgl-menu-space"></div>
        <div class="bgl-menu-links">
          <a
              href=""
              class="bgl-close-menu-btn"
          ><img
    src="../assets/close.svg"
    height=""
    width=""
 /></a>
          <a
              href=""
              class="bgl-menu-link"
          >Link</a><a
                       href=""
                       class="bgl-menu-link"
                   >Link</a><a
                                href=""
                                class="bgl-menu-link"
                            >Link</a>
        </div>
        <a
            href=""
            class="bgl-menu-btn"
        ><img
    src="../assets/menu.svg"
    height=""
    width=""
 /></a>
      </div>
      <div class="bgl-w560">
        <h1 class="bgl-big-head">Welcome to Bagel studio</h1>
        <p class="bgl-text">Hi on this page you will find all kinds of elements that can be used in different projects</p>
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
            <a
                href=""
                class="bg-dropdown-link"
            >Link</a>
            <a
                href=""
                class="bg-dropdown-link"
            >Link</a>
            <a
                href=""
                class="bg-dropdown-link"
            >Link</a>
          </div>
        </div>
        <div class="center"><a
    href=""
    class="bgl-btn"
>Click me!</a><a
                  href=""
                  class="bgl-btn line"
              >Click me!</a></div><div class="bgl-popup-wrap"><a
    href=""
    class="bgl-btn"
>Pop me!</a>
    <div class="bgl-popup-background"><a
    href=""
    class="bgl-close-popup"
>
    <img
        src="../assets/close.svg"
        height=""
        width=""
        class=""
     /></a>
    <div class="bgl-popup-content-wrap"><div class="bgl-popup-box"><img
    src="https://via.placeholder.com/150"
    height=""
    width=""
 />
    <p>This is my popup, there's no other like it, and I can pop it if I like</p><a
                                                                                     href=""
                                                                                     class="bgl-btn"
                                                                                 >Popup&nbsp;</a></div></div></div></div>
        <div class="bgl-box">
          <p class="bgl-text">this is a box a very simple box</p>
        </div>
        <div class="bgl-form">
          <form
              action="/"
              class=""
          >
            <label
                for=""
                class="bgl-label"
            >label</label><input
                              placeholder="Name"
                              type="text"
                              id=""
                              name=""
                              class="bgl-input"
                           /><label
                                 for=""
                                 class="bgl-label"
                             >label</label><input
                                               placeholder="Email"
                                               type="email"
                                               id=""
                                               name=""
                                               class="bgl-input"
                                            /><label
                                                  for=""
                                                  class="bgl-label"
                                              >label</label><textarea
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
              <label
                  for=""
                  class="bgl-radio-label"
              >radio1</label>
            </div>
            <div class="bgl-radio-wrap">
              <input
                  type="radio"
                  id=""
                  name="radio"
                  value="radio2"
                  checked=""
                  class="bgl-radio"
               /><label
                     for="radio2"
                     class="bgl-radio-label"
                 >radio2</label>
            </div>



            <div class="bgl-checkbox-wrap">
              <input
                  class="bgl-checkbox"
                  type="checkbox"
                  id="bglcheckbox"
                  name="bglcheckbox"
                  checked=""
               />
              <label
                  class="bgl-checkbox-label"
                  for="bglcheckbox"
              >checkbox</label>
            </div>

            <input
                type="submit"
                id=""
                value="Submit"
                class="bgl-form-btn"
             />
          </form>
          <div class="bgl-form-success">
            <p>Thank you for getting in touch!</p>
          </div>
          <div class="bgl-form-fail">
            <p>Something went wrong while sending the form</p>
          </div>
        </div>
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
          <a
              href=""
              class="soc-link"
          >
            <img
                src="../assets/facebook.svg"
                height=""
                width=""
             /></a><a
                       href=""
                       class="soc-link"
                   >
            <img
                src="../assets/linkedin.svg"
                height=""
                width=""
             /></a><a
                       href=""
                       class="soc-link"
                   >
            <img
                src="../assets/twitter.svg"
                height=""
                width=""
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
