<template>
<div>
  <div class="hero invite">
    <div class="w1200 top invite">
      <div class="main-txt-side-new invite">
        <h1 class="head-64 top-invite"><span class="invitername"> </span> invited you to try out Groove!</h1>
      </div>
      <div class="invite-form w-clearfix w-form">
        <form data-name="accept-invite" name="wf-form-accept-invite" bagelform="true" class="invite-form-inner">
          <div class="w-embed"><input id="referrerUid" name="referrerUid" type="hidden">
            <input id="referrerName" name="referrerName" type="hidden">
          </div><input type="text" class="field smaller w-input" maxlength="256" name="firstName" data-name="firstName" placeholder="First name:" id="firstName" required=""><input type="email" class="field smaller w-input" maxlength="256" name="email" data-name="email" placeholder="Email:" id="email-2" required=""><input type="submit" value="I’m In" data-wait="Please wait..." class="join-btn full w-button">
        </form>
        <div class="success-message invite w-form-done">
          <div class="success-invite-txt-desktop"><span class="green">You’ve accepted </span><span class="green invitername"> </span><span class="green">’s invite 🎉<br></span><br>Please open this page on a mobile device (not a laptop!) and download -<br><br>“Groove: Beyond work”<br><br>in the <a href="https://apps.apple.com/vn/app/groove-beyond-work/id1534708215" target="_blank" class="store-link"><strong>App Store</strong></a> or <a href="https://play.google.com/store/apps/details?id=io.grooveapp.app" target="_blank" class="store-link"><strong>Google Play</strong></a>.</div>
          <div class="success-invite-txt-mobile">You’ve accepted <span class="invitername"> </span>’s invite 🎉<br><br>Go ahead and download the Groove app - see you there:<span class="text-span"><br></span>
            <a href="https://apps.apple.com/vn/app/groove-beyond-work/id1534708215" target="_blank" class="store-link store"><span class="text-span store">App Store</span></a>
            <a href="https://play.google.com/store/apps/details?id=io.grooveapp.app" target="_blank" class="store-link store play"><span class="text-span store">Google Play</span></a>
          </div>
        </div>
        <div class="error-message invite w-form-fail">
          <div>We’re sorry! There seems to be a connection issue. Please try again in a few minutes.</div>
        </div><img src="@/assets/GROOVE-editor-1-.png" loading="eager"  alt="" class="invite-image">
      </div>
    </div>
    <div class="ooo invite"></div>
  </div>
  <div class="accomplish-sec wf-section">
    <div class="app-head-wrap">
      <h2 class="head-64">What can you accomplish in a Groove?<br></h2>
      <p class="small-sub pad">Craft a more intentional day that helps you build the life you want.<br></p>
    </div>
    <div class="acmp-card-wrap">
      <div class="acmp-card">
        <div class="acmp-image-wrap"><img src="@/assets/2477015.jpg" loading="lazy" alt="Find Your Team" class="acmp-image"></div>
        <p class="acmp-small-head">Find your<br>team<br></p>
        <p class="acmp-txt">Meet your new coworkers: Groove&#x27;s global community of creatives — offering accountability and encouragement. <br></p>
      </div>
      <div class="acmp-card">
        <div class="acmp-image-wrap"><img src="@/assets/2514210-1.jpg" loading="lazy"  alt="A more satisfying day" class="acmp-image"></div>
        <p class="acmp-small-head">A more<br>satisfying day<br></p>
        <p class="acmp-txt">On-demand Grooves fit seamlessly into your workday and enhance your routine. We&#x27;re here to fill your cup, not drain it.<br></p>
      </div>
      <div class="acmp-card">
        <div class="acmp-image-wrap"><img src="@/assets/1722963.jpg" loading="lazy" alt="Create your definition of 
accomplishment" class="acmp-image"></div>
        <p class="acmp-small-head">Create your definition of &#x27;accomplishment&#x27; <br></p>
        <p class="acmp-txt">Stay focused without distractions so you can get more done and fulfill your goals.<br></p>
      </div>
    </div>
  </div>
</div>
</template>