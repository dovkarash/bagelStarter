<template>
  <div class="home">
    <div class="bagel-wrap">
      <div class="pattern-wrap"><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div><div class="oval"></div></div>
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
        <div
            class="bgl-menu-links"
            :class="{ open: openSideBar }"
        >
          <div
              @click="openSideBar = false"
              href=""
              class="bgl-close-menu-btn"
          >
            <img
                src="../assets/close.svg"
                height=""
                width=""
             />
          </div>
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
        <div
            @click="openSideBar = true"
            class="bgl-menu-btn"
        >
          <img
              src="../assets/menu.svg"
              height=""
              width=""
           />
        </div>
      </div>
      <div class="bgl-w560">
        <h1 class="bgl-big-head">Welcome to Bagel studio</h1>
        <p class="bgl-text">
          Hi on this page you will find all kinds of elements that can be used
          in different projects
        </p>
        <div
            class="bgl-dropdown"
            :class="{ open: opendropdown }"
        >
          <div
              class="bgl-dropdown-head"
              @click="opendropdown = !opendropdown"
          >
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
        <div class="center">
          <a
              href=""
              class="bgl-btn"
          >Click me!</a><a
                            href=""
                            class="bgl-btn line"
                        >Click me!</a>
        </div>
        <div class="bgl-box">
          <p class="bgl-text">this is a box a very simple box</p>
        </div>
        <div class="bgl-popup-wrap center">
          <button
              @click="openPopup = true"
              href=""
              class="bgl-btn"
          >Pop me!</button>
          <div
              class="bgl-popup-background"
              :class="{ open: openPopup }"
          >
            <div
                class="bgl-close-popup"
                @click="openPopup = false"
            >
              <img
                  src="../assets/close.svg"
                  height=""
                  width=""
                  class=""
               />
            </div>
            <div class="bgl-popup-content-wrap">
              <div class="bgl-popup-box">
                <img
                    src="../assets/eatMe.svg"
                    height=""
                    width=""
                    class="bgl-popup-img"
                 />
                <h4>This is my popup</h4>
                <p>there's no other like it, and I can pop it if I like</p>
                <a
                    href=""
                    class="bgl-btn"
                >Popup&nbsp;</a>
              </div>
            </div>
          </div>
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
            <div
                class="bgl-tab-head"
                @click="tab = 1"
                :class="{ open: tab === 1 }"
            >
              <p>Tab 1</p>
            </div>
            <div
                class="bgl-tab-head"
                @click="tab = 2"
                :class="{ open: tab === 2 }"
            >
              <p>Tab 2</p>
            </div>
            <div
                class="bgl-tab-head"
                @click="tab = 3"
                :class="{ open: tab === 3 }"
            >
              <p>Tab 3</p>
            </div>
          </div>
          <div class="bgl-tabs-content">
            <div
                class="bgl-tab"
                :class="{ open: tab === 1 }"
            >
              <p>Text for tab 1</p>
            </div>
            <div
                class="bgl-tab"
                :class="{ open: tab === 2 }"
            >
              <p>Text for tab 2</p>
            </div>
            <div
                class="bgl-tab"
                :class="{ open: tab === 3 }"
            >
              <p>Text for tab 3</p>
            </div>
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
  data: () => ({
    opendropdown: false,
    openPopup: false,
    openSideBar: false,
    tab: 1,
  }),
  name: "Home",
};
</script>
