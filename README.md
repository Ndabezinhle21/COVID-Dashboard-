# COVID-Dashboard-
OPenParly Hackathon Entry

OpenParly-COVID-Tracker-Bot

Messenger Bot- Landing Page
https://chatfuel.com/bot/OpenParly-COVID-Tracker-Bot-100113001694935
Chat Url
m.me/100113001694935

Website Intergration Stript For Chat Buble at Bottom of Page


<script>
  var div = document.createElement('div');
  div.className = 'fb-customerchat';
  div.setAttribute('page_id', '100113001694935');
  div.setAttribute('ref', '');
  document.body.appendChild(div);
  window.fbMessengerPlugins = window.fbMessengerPlugins || {
    init: function () {
      FB.init({
        appId            : '1678638095724206',
        autoLogAppEvents : true,
        xfbml            : true,
        version          : 'v3.3'
      });
    }, callable: []
  };
  window.fbAsyncInit = window.fbAsyncInit || function () {
    window.fbMessengerPlugins.callable.forEach(function (item) { item(); });
    window.fbMessengerPlugins.init();
  };
  setTimeout(function () {
    (function (d, s, id) {
      var js, fjs = d.getElementsByTagName(s)[0];
      if (d.getElementById(id)) { return; }
      js = d.createElement(s);
      js.id = id;
      js.src = "//connect.facebook.net/en_US/sdk/xfbml.customerchat.js";
      fjs.parentNode.insertBefore(js, fjs);
    }(document, 'script', 'facebook-jssdk'));
  }, 0);
</script>
