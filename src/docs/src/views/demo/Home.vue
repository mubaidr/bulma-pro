<template>
  <div>
    <section class="section">
      <div class="container">
        <h1 class="title">
          Getting started
        </h1>

        <hr>

        <div class="content">
          <p>
            You can either:
          </p>
          <ol>
            <li>
              use
              <strong>npm</strong> to install the <em>bulma-pro</em> package
            </li>
            <li>
              use
              <strong>CDN</strong>
            </li>
            <li>
              use the
              <strong>GitHub repository</strong> to get the latest development version
            </li>
          </ol>
          <ol class="padded-list">
            <li>
              <span class="title is-5">Use npm:
              </span>
              <p>
                <a href="https://nodei.co/npm/bulma-pro/"><img src="https://nodei.co/npm/bulma-pro.png?compact=true"></a>
              </p>
              <p>
                <pre>
<code>
import 'bulma-pro/css/bulma.css'</code>
                </pre>
                OR <br>
                <pre>
<code>
import 'bulma-pro/bulma.sass'</code>
                </pre>
              </p>
            </li>
            <li>
              <span class="title is-5">CDN link</span>
              <p>
                <a href="https://unpkg.com/bulma-pro/css/">unpkg.com/bulma-pro</a>
              </p>
            </li>
            <li>
              <span class="title is-5">
                Download from the repository:
              </span>
              <p>
                <a href="https://raw.githubusercontent.com/mubaidr/bulma-pro/master/css/bulma.min.css">https://github.com/mubaidr/bulma-pro/tree/master/css</a>
              </p>
            </li>
          </ol>
        </div>

        <div class="content">
          <h2 class="subtitle is-3">
            Customize
          </h2>
          <p>Simply set your own Sass variables before importing bulma-pro.</p>
          <p>
            <pre>
            <code>
// Set your brand colors
$primary: #8A4D76
$info: #FA7C91
$success: #757763
$warning: yellow
$danger: red
$light: #ccc
$dark: #444

// Update font family
$family-sans-serif: "Calibri", "Arial"

// Import the bulma-pro
@import "bulma-pro/bulma.sass"
            </code></pre>
          </p>
        </div>

        <div class="content">
          <h2 class="subtitle is-3">
            Documentation
          </h2>
          <p>
            You can follow
            <a href="https://bulma.io/documentation/">official bulma documentaion</a> for all components.
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {}
</script>

<style>
.padded-list li {
  padding: 1em 0;
}
</style>
