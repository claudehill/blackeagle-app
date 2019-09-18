<template>
  <div class="app-cmp-wrapper">
    <div class="domain_search_home">
      <div class="container">
        <div id="ir_wrapper" style="margin: 0px auto; max-width: 100%;">
          <div class="row">
            <div class="col-12 col-lg-6 mx-auto my-auto">
              <h4
                class="text-white"
                style="margin: 0.75em 0px 0.75em; font-size: 1.25em; line-height: 1.5em; font-family: -apple-system, blinkmacsystemfont, 'segoe ui', roboto, oxygen, ubuntu, cantarell, 'fira sans', 'droid sans', 'helvetica neue', sans-serif;"
              >
                Find a perfect domain. Starting at
                <span class="offer">just $0.88!</span>
              </h4>
            </div>

            <div class="col-12 col-lg-6">
              <form
                id="ir_form"
                method="GET"
                target="_blank"
                action="https://namecheap.pxf.io/c/1881477/386170/5618"
              >
                <div
                  class="nc-search"
                  role="search"
                  style="position: relative; display: flex; flex-flow: row wrap; margin: 0px auto; padding: 0.75em 0px 0.75em; font-family: -apple-system, blinkmacsystemfont, 'segoe ui', roboto, oxygen, ubuntu, cantarell, 'fira sans', 'droid sans', 'helvetica neue', sans-serif;"
                >
                  <input id="ir_link" name="u" type="hidden" />
                  <input
                    id="ir_domain"
                    name="domain"
                    style="flex: 1 1 0%; 
                    min-width: 60px; 
                    min-height: 42px; padding: 0px 0.5em; 
                    border: 1px solid #d6d6d6; font-size: 1.125em; 
                    line-height: 20px; margin-right: 0px !important; margin-top: 0px !important; 
                    border-radius: 0px"
                    autocomplete="off"
                    placeholder="e.g. example.com"
                    autocorrect="off"
                    spellcheck="false"
                    autocapitalize="off"
                    type="text"
                  />
                  <input
                    style="flex: 0 1 0%; 
                    min-width: 94px; width: 94px; padding: 0px 1em; font-size: 1.125em; line-height: 20px; text-align: center; border: 1px solid rgb(214, 214, 214); 
                    color: #fff;
                    text-shadow: rgb(214, 214, 214) 0px -1px 1px; 
                    background: #970001;
                    cursor: pointer; min-height: 42px !important; 
                    margin-left: 0px !important; 
                    margin-top: 0px !important; 
                    border-radius: 0px 0px 0px 0px !important;"
                    value="Search"
                    type="submit"
                  />
                </div>
              </form>
              <div class="powerby">
                <p style="display:none;">
                  powered by
                  <a
                    id="ir_url"
                    href="https://namecheap.pxf.io/c/1881477/386170/5618"
                    target="_blank"
                    style="font-weight: bold; color: #de3723; text-decoration: none;"
                  >Namecheap</a>
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <script type="application/javascript">
  !(function() {
    var e = document.querySelector("#ir_form"),
      n = document.querySelector("#ir_domain"),
      t = document.querySelector("#ir_link");
    e.addEventListener("submit", function(o) {
      o.preventDefault(),
        (t.value =
          "https://www.namecheap.com/domains/registration/results.aspx?domain=" +
          n.value);
      if (e.domain.value === "") {
        window.location.href = document.querySelector("#ir_url").href;
      } else {
        e.submit();
      }
    });
  })();
    </script>
  </div>
</template>

<script>
export default {
  mounted() {
    // let domainSearchScript = document.createElement("script");
    // domainSearchScript.setAttribute();
  }
};
</script>

<style scoped>
/**color: #6d6e70; */
.offer {
  font-style: italic;
  font-weight: bold;
  color: #74ca04;
}
</style>