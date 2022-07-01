---
layout: home
---

<div>
  <div id="backgroundVideoContainer">
    <video autoplay muted loop id="backgroundVideo">
      <source src="{{ site.baseurl }}/public/video/banner-video.mp4" type="video/mp4">
    </video>
    <div id="videoHeader">
      <img class="headervidlink" src="{{ site.baseurl }}/public/img/logo-splash.png">
    </div>
  </div>
  <div class="sectionTriButton">
    <button class="triButton backgroundImageDark triButtonBackground1">
      <a href="{{ site.baseurl }}/sustainability/">SUSTAINABILITY</a>
    </button>
    <button class="triButton backgroundImageDark triButtonBackground2">
      <a href="{{ site.baseurl }}/events/">QUARTERLY EVENTS</a>
    </button>
    <button class="triButton backgroundImageDark triButtonBackground3">
      <a href="{{ site.baseurl }}/patreon/">PATREON</a>
    </button>
  </div>
  <div class="sectionGameCatalog">
    <div class="section verticalPaddingXLarge">
      <div class="sectionColumnFullWidth">
        <h2>Something For Everyone</h2>
      </div>
    </div>
    <div class="sectionGameRow">
      {% for i in (1..site.data.games.banners.repeat) %}
        {% for url in site.data.games.banners.assets %}
          <img class="gameCatalogItem" src="{{ site.baseurl }}/public/img/{{ url }}">
        {% endfor %}
      {% endfor %}      
    </div>
  </div>
</div>

<div id="container">
  <div id="content">
    <div class="heightXXLarge"></div>
    <div class="section hideTopBorder backgroundGame1 backgroundImageDark backgroundImageCenter sectionBorderTop sectionBorderBottom">
      <div class="sectionColumnSub">
        <button class="navButton">
          <a href="{{ site.baseurl }}/join/">JOIN NOW</a>
        </button>
      </div>
      <div class="sectionColumnMain">
        <h2>We’ve got your six</h2>
        <p class="bold">       
        Never game alone. From first-person shooters to wacky party games, and massive-multiplayer experiences in between, there's always room in our party. Come play with us and together we'll discover your next adventure!
        </p>
      </div>
    </div>
    <div class="section backgroundGame2 backgroundImageDark backgroundImageCenter sectionBorderTop sectionBorderBottom">
      <div class="sectionColumnMain">
        <h2>Gaming Is Who We Are</h2>
        <p class="bold">
        Derp Company is about connecting adult (18+) gamers to create fun team-based gameplay experiences. We want to make it easier to jump in, socialize, and play with people who care about a positive team experience in any game.
        </p> 
        <p class="bold">
        Founded in 2012 in the game Planetside 2, Derp Company has grown into a multi-gaming PC community bringing cooperative experiences throughout the titles we play. We are a home for passionate people who value our mission—empowering an open, fun, PC gaming environment that inspires team play.
        </p>
      </div>
      <div class="sectionColumnSub">
      </div>
    </div>
    <div class="section sectionBorderTop sectionBorderBottom">
      <div class="sectionColumnSub">
        <button class="navButton">
          <a href="{{ site.baseurl }}/patreon/">SIGN ME UP</a>
        </button>
      </div>
      <div class="sectionColumnMain">
        <h2>Become A Member</h2>
        <p class="bold">
        Our membership is important to us, so we've packed it full of amazing perks and benefits. 
          •  Earn points each time you play in quarterly events<br><br>
          •  Ability to create custom temporary game channels<br><br>
          •  Unlock joining our Social Groups<br><br>
          •  Exclusive member-only raffles<br><br>
          •  Access to #memes [NSFW]<br><br>
        </p>
      </div>
    </div>
    <div class="section">
      <div class="sectionColumnMain">
        <iframe id="discordEmbed" src="https://discord.com/widget?id=154310693171101697&theme=dark" allowtransparency="true" frameborder="0" sandbox="allow-popups allow-popups-to-escape-sandbox allow-same-origin allow-scripts"></iframe>
      </div>
      <div class="sectionColumnSub">
        <button class="navButton">
          <a href="http://discord.derpcompany.com/">JOIN DISCORD</a>
        </button>
      </div>
    </div>
  </div>
</div>