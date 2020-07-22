<template>
  <div class="main">
    <h1>{{ msg }}</h1>
    <p>
      Voor hulp op afstand belt u <a href="tel:0547-292768">0547-292768</a> tijdens onze openingstijden. </p><p>Let op! Hier kunnen kosten aan verbonden zijn.
    </p>
    <a href="https://download.anydesk.com/AnyDesk.exe"><h3>Download hier AnyDesk</h3></a>
    <br><br>
    <div class="overiglinks">
        <li>
          <ul><b><p>Overige Links:</p></b></ul>
          <ul><a href="https://dahuawiki.com/images/Files/Software/SmartPSS/DH_SMARTPSS-Win64_En_IS_V2.003.0000001.0.R.200413.zip"><p>SmartPSS</p></a></ul>
          <ul><a href="https://dahuawiki.com/images/Files/Software/Dahua_Toolbox/Dahua_ToolBox_Eng_V1.02.1.T.20170314.zip"><p>Dahua Toolbox</p></a></ul>
          <ul><a href="https://www.advanced-ip-scanner.com/download/Advanced_IP_Scanner_2.5.3850.exe"><p>Advanced IP Scanner</p></a></ul>
        </li>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Main',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #2e7aa3;
}
ul {
  display: inline-block;
  padding: 20px;
}
</style>
