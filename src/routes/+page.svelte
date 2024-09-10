<script>
  import animals from "$lib/img/animals.png";
  import bg from "$lib/img/bg.gif";
  import buynow from "$lib/img/buy_now.png";
  import fbico from "$lib/img/facebook_icon.png";
  import logopps from "$lib/img/logo_pps.png";
  import logo from "$lib/img/logo.png";
  import topbg from "$lib/img/top-bg.gif";
  import tumblr from "$lib/img/Tumblr.png";
  import twitter from "$lib/img/Twitter.png";
</script>

<div id="centerpage">
  <div id="toppanel" style="z-index: 3;">
    <div class="top_center" style="height: 48px; width: 100%;">
      <table style="height: 48px; width: 100%;">
        <tbody>
          <tr>
            <td style="width: 244px; height: 48px; padding: 0px; top: 0px;">
              <div id="prepurchasesplash" style="height: 88px;">
                <a href="http://minecraftbeta.net/"
                  ><img
                    src={logo}
                    width="243"
                    height="46"
                    alt="MinecraftBeta.net Logo"
                  />
                </a>
              </div>
            </td>
            <td>
              <div id="links">
                <a
                  href="http://minecraftbeta.net/"
                  id="menu_"
                  class="menuItem"
                  style="text-decoration: underline;">Home</a
                >&nbsp; &nbsp;
                <a
                  href="https://discord.gg/PnTjYTt2vR"
                  id="menu_community"
                  class="menuItem"
                  style="background: none;"
                  target="_blank">Discord</a
                >&nbsp; &nbsp;
                <a
                  href="http://map.minecraftbeta.net/"
                  id="menu_merch"
                  class="menuItem">World Map</a
                >&nbsp;
                <!-- &nbsp; <a href="#" id="menu_help" class="menuItem" style="background: none;">Forum</a>&nbsp; &nbsp; -->
              </div>
            </td>

            <td>
              <div id="loginpanel">
                <a href="/" class="loginpanel">Log in</a> |
                <a href="/" class="loginpanel">Register</a>
              </div>
            </td>
          </tr>
        </tbody>
      </table>
    </div>
    <br />
    Est. 19/03/2023 🚀<br />
    19/03/2023 - World border set 2048 blocks from spawn.
  </div>

  <div id="toppanel_bg" style="z-index: 1;"></div>

  <div id="page" style="z-index: 4;"></div>

  <div id="content">
    <div style="margin-left:0px;">
      <table style="width:900px;">
        <tbody
          ><tr>
            <td style="width: 600px;">
              <br /><br /><br />

              <div class="videoEmbed">
                <object aria-label="video" width="650" height="385"
                  ><param
                    name="movie"
                    value="https://www.youtube.com/v/m_yqOoUMHPg?fs=1&amp;color1=0x3a3a3a&amp;color2=0x999999"
                  /><param name="allowFullScreen" value="true" /><param
                    name="allowscriptaccess"
                    value="always"
                  /><embed
                    src="https://www.youtube.com/v/m_yqOoUMHPg?fs=1&amp;color1=0x3a3a3a&amp;color2=0x999999"
                    type="application/x-shockwave-flash"
                    width="640"
                    height="385"
                  /></object
                >
              </div>
              <p style="font-size:13px; padding-top: 20px">
                MinecraftBeta.net is a server designed to revive the original
                survival multi-player experience and provide an oldschool,
                classic experience for nostalgia seeking Minecraft players.
              </p>
              <!-- <p style="font-size:13px;">Minecraft is a game about placing blocks to build anything you can imagine. At night monsters come out, make sure to build a shelter before that happens.</p> -->
            </td>
            <td
              style="width:300px; text-align:center; vertical-align:text-top;"
            >
              <!-- <img src="img/figurer.jpg" style="border: 1px solid yellow; width: 250px; height:300px;"> -->

              <div
                style="width: 300px; height:400px; margin-left: 50px; margin-top: -10px; text-align:center;"
              >
                <div
                  style="margin-left: 0px; margin-top: 70px; text-align:center;"
                >
                  <img src={animals} alt="Animals" width="300" height="202" />
                </div>

                <div
                  style="margin-left: 50px; margin-top: 10px; text-align:center;"
                >
                  <a href="/"
                    ><img src={buynow} class="linkButton" alt="Join Now" /></a
                  >
                </div>

                <br />
                <br />
                <p style="font-size:15px;">
                  We're using Minecraft Beta (Version 1.7.3):<br />
                  Server IP:
                  <!-- <a href="a">play.placeholder.net</a> | -->
                  <a href="/" class="underline">play.minecraftbeta.net</a>
                  <br />
                </p>
                <p style="font-size:11px;">
                  (Make sure to enable beta versions in your launcher.)
                  <br />
                  <br />

                  Don't own Minecraft? No problem.<br />
                  <a href="https://tlauncher.org/" class="underline"
                    >Download TLauncher</a
                  >
                </p>
              </div></td
            >
          </tr></tbody
        >
      </table>
    </div>

    <div
      style="background:none; width:1024px; margin-left: -30px; margin-bottom: -40px;"
    >
      <div class="socialscontent">
        <iframe
          title="discord"
          src="https://discord.com/widget?id=1087433522760929350&theme=dark"
          width="350"
          height="700"
          style="margin-left: 32px;"
          frameborder="0"
          sandbox="allow-popups allow-popups-to-escape-sandbox allow-same-origin allow-scripts"
        ></iframe>
        <div class="tweets">
          <a
            class="twitter-timeline"
            data-theme="dark"
            href="https://twitter.com/BigJax369?ref_src=twsrc%5Etfw"
            >Tweets by jax</a
          >
          <script
            async
            src="https://platform.twitter.com/widgets.js"
            charset="utf-8"
          ></script>
        </div>
      </div>
    </div>
  </div>
  <!-- page end-->
</div>
<!-- pagecenter end-->

<div class="footer" id="footer">
  Made with ❤️ by <a href="http://twitter.com/bigjax_eth/">BigJax</a>.
  <!-- Copyright 2009-2011 Mojang AB. <a href="http://www.minecraft.net/copyright.jsp">Terms and conditions</a>. <a href="http://www.minecraft.net/credits.jsp">Credits</a>. -->
</div>
