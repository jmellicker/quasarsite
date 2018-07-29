<template>
  <q-page>
    <div>
    
      <div align="center" style="padding: 8rem; background: #000; color: #fff;">
        <div class="brandFont allCaps" style="font-size: 2rem; letter-spacing: 2rem; color: #fff;">welcome to</div>
        <div class="brandFont" style="font-size: 30rem; margin: -1rem; color: #027be3;">Q</div>
        <div class="brandFont allCaps" style="font-size: 6rem; color: #027be3; font-weight: 700;">q<span style="color: #fff;">uasar</span></div>
        <div class="brandFont allCaps" style="font-size: 1.2rem; letter-spacing: 0rem; color: #fff;">the front end framework from the future</div>
      </div>

      <div class="row full-width" align="center" style="text-align: left;">
        <!-- <img alt="Quasar goes everywhere" src="~assets/quasar_goes_everywhere.png" style="width: 100%;"> -->
        <div class="col" style="padding: 2rem; line-height: 1.8rem;">
          <h3 style="margin-bottom: 1rem;">What is Quasar?</h3>
          <p>Quasar is a complete solution for building any kind of awesome experience for browser, server, mobile and desktop app you can dream of.</p>
          <!-- <p>Ever wish there was just one comprehensive front end solution you could master and use that
            offered everything you need to build anything you can dream up?</p>
          <p>You found it!</p> -->
          <p>Powered by modern, proven, leading technologies, like Vue.js, Flexbox,
             Webpack, Cordova and Electron, Quasar is jam-packed with features and power,
             from an extensive component and CSS library to a suite of utilities to
             make your development experience fast and fun.</p>
          <p>Thousands of companies and developers around the world are using Quasar in production to build world class web applications,
             mobile apps and desktop apps for major brands.</p>
          <p>Developers are switching to Quasar every day... will you be one of them?</p>
        </div>
        <div class="col" style="padding: 2rem; line-height: 1.8rem;">
          <img alt="Quasar goes everywhere" src="~assets/quasar_goes_everywhere.png" style="width: 100%;">
        </div>
      </div>
    </div>

      <div class="row full-width" align="center" style="text-align: left;">
        <div class="col" style="padding: 2rem; background: #027be3; line-height: 1.8rem; color: #fff;">
          <h4 align="center" style="margin: 1rem;">Unparalleled developer experience through Quasar CLI</h4>
          <p>The Quasar CLI enables you to scaffold a project in less than a minute based on modern development
              best practices:</p>
          <ul>
            <li>a state-preserving hot-reload environment (even on your mobile devices!)</li>
            <li>HTML/CSS/JS minification</li>
            <li>cache busting</li>
            <li>tree shaking</li>
            <li>source mapping</li>
            <li>ES6 transpiling</li>
            <li>code linting</li>
            <li>accessibility features</li>
          </ul>
          Quasar takes care of all these and more - no configuration needed.
        </div>
        <div class="col" style="padding: 2rem; line-height: 1.8rem;">
          <h4 align="center" style="margin: 1rem;">Wide platform support</h4>
          <p>Code once, deliver anywhere.</p>
          <ul>
            <li>browser support: Google Chrome, Firefox, IE11/Edge, Safari, Opera, iOS, Android, Windows Phone, Blackberry and more</li>
            <li>SPAs (Single Page Apps)</li>
            <li>SSR (Server-side Rendered Apps) (+ optional PWA client takeover)</li>
            <li>PWAs (Progressive Web Apps)</li>
            <li>Mobile Apps (Android, iOS, Windows) with Apache Cordova</li>
            <li>Desktop Apps (MacOS, Windows, Linux) with Electron</li>
          </ul>
        </div>
      </div>

      <div class="row full-width" align="center" style="text-align: left;">
        <div class="col" style="padding: 2rem;">
          <img src="~assets/screenshot6.jpg" style="width: 100%;">
        </div>
        <div class="col" style="padding: 2rem; background: #027be3; line-height: 1.8rem; color: #fff;">
          <h4 align="center" style="margin: 1rem;">Over 100 UI components, widgets and variations</h4>
          Quasar components are carefully crafted to provide the best possible experience to users on any size
           screen, from smartphones to computer monitors. Quasar is designed with performance in mind, so the
           overhead of Quasar is barely noticable.
          <ul>
            <li>layout and navigation components from toolbars and tabs to breadcrumbs and side menus</li>
            <li>form elements like buttons, fields, select menus, chips and sliders</li>
            <li>user notification elements like dialogs, modals, action sheets, popovers and tooltips</li>
            <li>special components like a datatable, rich text editor, uploader, carousel, timeline and datepicker</li>
          </ul>
        </div>
      </div>
    </div>

  </q-page>
</template>

<style>
h1, h2, h3, h4, h5, h6 {
  text-transform: uppercase;
  font-family: 'Spinnaker', 'Helvetiva-Neue', 'Helvetica', 'Arial', sans-serif;
}
li {
  margin-bottom: .5rem;
}
.brandFont {
  font-family: 'Spinnaker', 'Helvetiva-Neue', 'Helvetica', 'Arial', sans-serif;
}
.brandColor {
  background: #027be3;
}
.allCaps {
  text-transform: uppercase;
}
</style>

<script>
  export default {
    name: 'PageIndex'
  }
</script>
