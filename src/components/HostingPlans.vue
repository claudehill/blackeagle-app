<template>
  <div class="app-cmp-wrapper">
    <div class="section_holder33 two">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <h1 class="lt_title_big">
              Cloud
              <span>Hosting</span>Plans
            </h1>
            <div class="cl_title_line"></div>
            <p
              class="lt_title_bottomtext"
            >Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Suspendisse et justo. Praesent mattis commodo augue. Aliquam ornare hendrerit augue</p>
          </div>
        </div>

        <!-- TODO: make card with shadow based on https://codepen.io/sdthornton/pen/wBZdXq -->

        <div class="row">
          <div class="col-12 col-lg-3">
            <div class="price_table_holder">
              <div class="price_table shadow">
                <div class="plan_info">
                  <h2 class="title">Basic</h2>
                  <div class="price">
                    <sup>$</sup>9.99
                    <i>/ mo</i>
                  </div>
                  <ul class="plan_features two">
                    <li>1 GB Bandwidth</li>
                    <li>256 MB Memory</li>
                    <li>24/7 Full Support</li>
                    <li>256 MB Memory</li>
                    <li>24/7 Full Support</li>
                  </ul>
                  <div class="margin_top3"></div>
                  <a class="singup_but" href="#">Learn More</a>
                
                </div>

                <br />
                <br />
              </div>
            </div>
          </div>
          <div class="col-12 col-lg-3">
            <div class="price_table_holder">
              <div class="price_table shadow">
                <div class="plan_info">
                  <h2 class="title">Standard</h2>
                  <div class="price">
                    <sup>$</sup>29.99
                    <i>/ mo</i>
                  </div>
                  <ul class="plan_features two">
                    <li>1 GB Bandwidth</li>
                    <li>256 MB Memory</li>
                    <li>24/7 Full Support</li>
                    <li>256 MB Memory</li>
                    <li>24/7 Full Support</li>
                  </ul>
                  <div class="margin_top3"></div>
                  <a class="singup_but" href="#">Order Now</a>
                </div>
                <br />
                <br />
              </div>
            </div>
          </div>
          <div class="col-12 col-lg-3">
            <div class="price_table_holder">
              <div class="price_table active shadow">
                <div class="plan_info">
                  <h2 class="title">Premium</h2>
                  <div class="price">
                    <sup>$</sup>39.99
                    <i>/ mo</i>
                  </div>
                  <ul class="plan_features two">
                    <li>1 GB Bandwidth</li>
                    <li>256 MB Memory</li>
                    <li>24/7 Full Support</li>
                    <li>256 MB Memory</li>
                    <li>24/7 Full Support</li>
                  </ul>
                  <div class="margin_top3"></div>
                  <a class="singup_but" href="#">Order Now</a>
                </div>
                <br />
                <br />
              </div>
            </div>
          </div>

            <div class="col-12 col-lg-3">
              <div class="price_table_holder">
                <div class="price_table shadow">
                  <div class="plan_info">
                    <h2 class="title">Unlimited</h2>
                    <div class="price">
                      <sup>$</sup>69.99
                      <i>/ mo</i>
                    </div>
                    <ul class="plan_features two">
                      <li>1 GB Bandwidth</li>
                      <li>256 MB Memory</li>
                      <li>24/7 Full Support</li>
                      <li>256 MB Memory</li>
                      <li>24/7 Full Support</li>
                    </ul>
                    <div class="margin_top3"></div>
                    <a class="singup_but" href="#">Order Now</a>
                  </div>
                  <br />
                  <br />
                </div>
              </div>
            </div>



        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HostingPlans"
};
</script>

<style scoped>
/*section 33*/
.section_holder33 {
  width: 100%;
  padding: 35px 0 40px 0;
  margin: 0px;
  float: left;
  background-color: #e1e1e1;
}
.section_holder33.two {
  background-color: #fff;
  padding: 70px 0 70px 0;
}
.lt_title_line {
  height: 3px;
  padding: 0px;
  margin: 15px auto 20px;
  text-align: center;
  background: url(~/images/colors/darkred/title_line7.png) center top no-repeat;
}
.cl_title_line {
  height: 3px;
  padding: 0px;
  margin: 15px auto 20px;
  text-align: center;
  background: url(~/images/colors/darkred/title_line10.png) center top no-repeat;
}
.lt_title_line.two {
  background: url(~/images/colors/darkred/title_line9.png) center top no-repeat;
}
.lt_title_bottomtext {
  width: 60%;
  padding: 0px;
  margin: 0px auto 60px;
  text-align: center;
}
.section_holder33 .shadow_box {
  width: 100%;
  height: 40px;
  padding: 25px;
  /* float:left; */
  background: #fff;
  margin: 0;
  background: url(~/images/colors/darkred/site-img61.png) center top no-repeat;
}
.section_holder33 .price_table_holder {
  /* width:292px; */
  /* float: left; */
  padding: 0;
  /* margin: 1rem; */
}
.section_holder33 .price_table {
  width: 100%;
  /* float: left; */
  padding: 0;
  margin: 20px 0 0 0;
  text-align: center;
  background-color: #272727;
  border-right: 1px solid #4b4b4b;
  transition-property: background-color, color;
  transition-duration: 0.5s;
  transition-timing-function: ease-out;
}
.section_holder33 .price_table .title {
  width: 100%;
  font-size: 30px;
  font-weight: 600;
  padding: 20px 0 20px 0;
  color: #fff;
  text-align: center;
  margin: 0px 0 10px 0;
  border-bottom: 1px solid #4b4b4b;
}
.section_holder33 .price_table .price {
  color: #fff;
  font-size: 45px;
  font-weight: bold;
  line-height: 45px;
  text-align: center;
  padding: 8px 0px 8px;
  border-bottom: 1px solid #4b4b4b;
}
.section_holder33 .price_table .price sup {
  font-size: 22px;
  font-style: normal;
}
.section_holder33 .price_table .price i {
  font-size: 16px;
  font-style: normal;
  font-weight: 500;
}
.section_holder33 .price_table ul.plan_features {
  width: 100%;
  float: left;
  text-align: center;
  padding: 0;
  margin: 0;
}
.section_holder33 ul.plan_features li {
  width: 70%;
  color: #a9a9a9;
  text-align: center;
  padding: 8px 0;
  margin: 0 auto;
  border-bottom: 1px solid #4b4b4b;
}
.section_holder33 ul.plan_features.two li {
  width: 80%;
}
.section_holder33 .plan_info .singup_but {
  color: #fff;
  text-align: center;
  padding: 8px 30px;
  margin: 0 0px 25px 0px;
  background-color: #970001;
}
.section_holder33.two .plan_info .singup_but {
  color: #fff;
  background-color: #970001;
}
.section_holder33 .plan_info .singup_but:hover {
  color: #fff;
  background-color: #272727;
}

/*table active small arrows*/
.section_holder33 .price_table .arrow {
  position: absolute;
  width: 34px;
  height: 19px;
  padding: 0px;
  margin: -19px 0px 0px -34px;
  float: left;
  background: url(~/images/colors/darkred/site-img56.png) 0 0 no-repeat;
  z-index: 3;
}
.section_holder33 .price_table .arrow.two {
  margin: -19px 0px 0px 291px;
  background: url(~/images/colors/darkred/site-img57.png) 0 0 no-repeat;
}
.section_holder33 .price_table .arrow.three {
  margin: 458px 0px 0px -34px;
  background: url(~/images/colors/darkred/site-img58.png) 0 0 no-repeat;
}
.section_holder33 .price_table .arrow.four {
  margin: 458px 0px 0px 291px;
  background: url(~/images/colors/darkred/site-img60.png) 0 0 no-repeat;
}
/*table drop list*/

/*drop list 3*/
.section_holder33.smalltext {
  font-size: 13px;
  padding: 0px 5px 0px 0px;
  margin: 0px;
  float: left;
}
.section_holder33 select option {
  width: 100%;
  margin: 0px;
  padding: 5px 5px 5px 5px;
  border-bottom: 1px solid #e1e1e1;
}
.section_holder33 select option span {
  color: #970001;
  font-size: 12px;
}
.section_holder33 .dropbox_holder3 select {
  border: 1px solid #e1e1e1;
}
.section_holder33 label.custom-select3 {
  width: 100%;
  position: relative;
  display: inline-block;
}
.section_holder33.two .price_table .custom-select3 select {
  background: none repeat scroll 0% 0% #272727;
  border: 1px solid #3a3a3a;
  color: #a9a9a9;
}
.section_holder33 .price_table.active .custom-select3 select {
  display: inline-block;
  padding: 4px 3px 2px 5px;
  margin: 0px;
  font-family: inherit;
  font-style: inherit;
  font-variant: inherit;
  font-size-adjust: inherit;
  font-stretch: inherit;
  -moz-font-feature-settings: inherit;
  -moz-font-language-override: inherit;
  outline: medium none;
  line-height: 1.2;
  background: none repeat scroll 0% 0% #970001;
  color: #fff;
  font-size: 13px;
  font-weight: normal;
  width: 100%;
  border: 1px solid #4b4b4b;
}

/* Select arrow styling */
.section_holder33 .custom-select3:after {
  content: "▼";
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  font-size: 60%;
  line-height: 40px;
  padding: 0 7px;
  background: #fff;
  border-top: 1px solid #d9d9d9;
  border-right: 1px solid #d9d9d9;
  border-bottom: 1px solid #d9d9d9;
  color: #272727;
  pointer-events: none;
}
.section_holder33.two .price_table .custom-select3:after {
  color: #fff;
  background: #272727;
  border-top: 1px solid #3a3a3a;
  border-right: 1px solid #3a3a3a;
  border-bottom: 1px solid #3a3a3a;
}
/*hover styles*/
.section_holder33 .price_table .custom-select3:after {
  color: #fff;
  background: #970001;
  border-top: 1px solid #c93132;
  border-right: 1px solid #c93132;
  border-bottom: 1px solid #c93132;
}
.section_holder33.two .price_table:hover .custom-select3:after {
  color: #fff;
  background: #970001;
  border-top: 1px solid #c93132;
  border-right: 1px solid #c93132;
  border-bottom: 1px solid #c93132;
}
.section_holder33 .price_table:hover {
  background-color: #970001;
  padding: 0 0;
  margin: 20px 0 0 0;
}
.section_holder33 .price_table:hover .title {
  color: #fff;
  border-bottom: 1px solid #c93132;
}
.section_holder33 .price_table:hover .price {
  color: #fff;
  border-bottom: 1px solid #c93132;
}
.section_holder33 .price_table:hover .plan_features li {
  color: #fff;
  border-bottom: 1px solid #c93132;
}
.section_holder33 .price_table:hover .singup_but {
  color: #272727;
  background-color: #fff;
}
.section_holder33 .price_table:hover .custom-select3 select {
  background: none repeat scroll 0% 0% #970001;
  border: 1px solid #c93132;
  color: #fff;
}
/*active styles*/
.section_holder33 .price_table.custom-select3 select {
  color: #fff;
  background-color: #970001;
  border: 1px solid #c93132;
}
.section_holder33 .price_table.active .custom-select3:after {
  color: #fff;
  background: #970001;
  border-top: 1px solid #c93132;
  border-right: 1px solid #c93132;
  border-bottom: 1px solid #c93132;
}
.section_holder33 .price_table.active {
  position: relative;
  background-color: #970001;
  padding: 20px 0;
  margin: 0 0 0 0;
}
.section_holder33 .price_table.active .title {
  color: #fff;
  border-bottom: 1px solid #c93132;
}
.section_holder33 .price_table.active .price {
  color: #fff;
  border-bottom: 1px solid #c93132;
}
.section_holder33 .price_table.active .plan_features li {
  color: #fff;
  border-bottom: 1px solid #c93132;
}
.section_holder33 .price_table.active .singup_but {
  color: #272727;
  background-color: #fff;
}
.section_holder33 .price_table.active .custom-select3 select {
  background: none repeat scroll 0% 0% #970001;
  border: 1px solid #c93132;
}

.section_holder33.two .plan_info .singup_but {
  background-color: #970001;
}
.section_holder33 .price_table.active .singup_but {
  background-color: #fff;
}
.section_holder33 .price_table:hover .singup_but {
  background-color: #fff;
}

.section_holder33.two .price_table:hover .custom-select3:after {
  background: #970001;
  border-top: 1px solid #c93132;
  border-right: 1px solid #c93132;
  border-bottom: 1px solid #c93132;
}

.shadow {
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24);
  transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
}

.shadow:hover {
  box-shadow: 0 14px 28px rgba(0, 0, 0, 0.25), 0 10px 10px rgba(0, 0, 0, 0.22);
}
</style>