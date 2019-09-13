<template>
<div class="app-cmp-wrapper">

  <div class="domain_search_home">
    <div class="container">
      <div class="one_half">
        <ul class="tld_list">
          <li class="title">Top Domains</li>
          <li class="one">.com <span>$11.99</span></li>
          <li class="two">.org <span>$11.99</span></li>
          <li class="three">.net <span>$10.99</span></li>
        </ul>
      </div>
      <div class="one_half last">
        <form method="get" id="domain-searchform" action="blog.html">
          <div>
            <input class="input-text" name="dsearch" id="dsearch" value="Enter your Domain Name here..." onFocus="if (this.value == 'Enter your Domain Name here...') {this.value = '';}" onBlur="if (this.value == '') {this.value = 'Enter your Domain Name here...';}" type="text" />
            <select class="drlist">
              <option value=".com">.com</option>
              <option value=".co">.co</option>
              <option value=".net">.net</option>
              <option value=".org">.org</option>
              <option value=".biz">.biz</option>
              <option value=".us.com">.us.com</option>
              <option value=".us">.us</option>
              <option value=".mobi">.mobi</option>
              <option value=".info">.info</option>
            </select>
            <input id="searchsubmit" value="Search" type="submit" />
          </div>
        </form>
      </div>
    </div>
  </div>


</div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>

</style>