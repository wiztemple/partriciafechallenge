<template>
<div id="app">
  <Navbar />
  <router-view />
</div>
</template>

<script>
import Navbar from "./components/Navbar";

export default {
  name: "App",
  components: {
    Navbar,
  },
};
</script>

<style>
html {
  line-height: 1.15;
  /* 1 */
  -webkit-text-size-adjust: 100%;
  /* 2 */
}

body {
  font-family: "Rubik", sans-serif;
  margin: 0;
  background-color: #f0f3f9;
}

h1 {
  font-size: 2em;
  margin: 0.67em 0;
}

img {
  border-style: none;
}

button,
[type="button"],
[type="reset"],
[type="submit"] {
  -webkit-appearance: button;
}

button::-moz-focus-inner,
[type="button"]::-moz-focus-inner,
[type="reset"]::-moz-focus-inner,
[type="submit"]::-moz-focus-inner {
  border-style: none;
  padding: 0;
}

button:-moz-focusring,
[type="button"]:-moz-focusring,
[type="reset"]:-moz-focusring,
[type="submit"]:-moz-focusring {
  outline: 1px dotted ButtonText;
}

[type="search"] {
  -webkit-appearance: textfield;
  /* 1 */
  outline-offset: -2px;
  /* 2 */
}

[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}

::-webkit-file-upload-button {
  -webkit-appearance: button;
  /* 1 */
  font: inherit;
  /* 2 */
}

[hidden] {
  display: none;
}

p {
  margin-bottom: 1rem;
}

button {
  background-color: transparent;
  background-image: none;
  padding: 0;
}

button:focus {
  outline: 1px dotted;
  outline: 5px auto -webkit-focus-ring-color;
}

html {
  font-family: "Poppins", sans-serif;
  line-height: 1.5;
  /* 2 */
}

*,
::before,
::after {
  box-sizing: border-box;
  /* 1 */
  border-width: 0;
  /* 2 */
  border-style: solid;
  /* 2 */
  border-color: #e2e8f0;
  /* 2 */
}

img {
  border-style: solid;
}

input::placeholder,
textarea::placeholder {
  color: #a0aec0;
}

button,
[role="button"] {
  cursor: pointer;
}

body {
  -webkit-font-smoothing: antialiased;
  -moz-font-smoothing: antialiased;
  font-family: "Poppins", sans-serif;
}

.columns {
  display: flex;
  flex-wrap: wrap;
  /* margin: 0 -0.9375rem; */
}

/*flex*/
.flex {
  display: flex;
}

/*button*/
.button {
  display: inline-block;
  font: inherit;
  position: relative;
  color: #222;
  font-weight: 400;
  text-align: center;
  white-space: nowrap;
  vertical-align: middle;
  user-select: none;
  border: 1px solid transparent;
  padding: 0.625rem 1.25rem;
  font-size: 1rem;
  line-height: 1.5;
  border-radius: 0.25rem;
  cursor: pointer;
}

.button-block {
  display: block;
  width: 100%;
}

.button:focus {
  outline: none;
}

.button-create {
  background-color: rgb(42, 88, 241);
  color: #fff;
  box-shadow: 0 1px 2px 0 rgba(60, 64, 67, 0.3),
    0 1px 3px 1px rgba(60, 64, 67, 0.15);
}

.button-google {
  border: 2px solid #eee;
}

.button-google>span:first-child {
  display: inline-block;
  position: relative;
  top: 3px;
  right: 5px;
}

.button-google>span:last-child {
  position: relative;
  top: -2px;
  left: 5px;
}

.input {
  position: relative;
}

.input-field {
  display: block;
  width: 100%;
  padding: 0.625rem 0.75rem;
  font-size: 1rem;
  line-height: 1.6;
  color: #222;
  background-clip: padding-box;
  background-color: rgba(247, 247, 247, 0.397);
  border: 1.5px solid rgba(0, 0, 0, 0.08);
  border-radius: 5px;
}

.input-icon {
  position: absolute;
  top: 42px;
  right: 15px;
}

.input-field:focus {
  outline: none;
  border-color: rgba(6, 98, 219, 0.795);
  transition: border-color ease-in-out 300ms;
}

.input-field::-moz-placeholder {
  color: rgba(54, 54, 54, 0.3);
}

.input-field:disabled,
.input-field:read-only {
  background-color: rgba(237, 237, 237, 0.2);
}

.input-field::-moz-placeholder,
.textarea::-moz-placeholder {
  color: rgba(54, 54, 54, 0.3);
}

.input-field::-webkit-input-placeholder {
  color: #c4c4c4;
}

/* auth */
.auth {
  width: 100vw;
  height: 100vh;
  overflow-y: scroll;
}

.auth-header {
  padding: 20px;
  font-weight: 700;
}

.auth-desc {
  position: relative;
  top: -15px;
  font-size: 14px;
  color: #777;
  padding-left: 20px;
}

.authbg {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  padding: 20px;
}

.authbg>img {
  width: 300px;
  height: 300px;
  object-fit: contain;
}

.form-label {
  display: block;
  padding-bottom: 5px;
}

.span-intro {
  font-size: 12px;
  color: rgb(68, 68, 73);
}

.check-auth-status {
  font-size: 12px;
  color: rgb(68, 68, 73);
}

.check-auth-status>a {
  text-decoration: none;
  color: rgb(17, 117, 218);
}

.authcard {
  width: 100%;
  height: 100vh;
  background: #fff;
  padding: 20px;
}

.formcard {
  padding-top: 50px;
}

/* utilities */
.mb-10 {
  margin-bottom: 10px;
}

.pt-10 {
  padding-top: 10px;
}

.pt-20 {
  padding-top: 20px;
}

@media (min-width: 768px) {
  .auth {
    overflow-y: hidden;
  }

  .authcard {
    padding: 100px;
  }

  .authbg {
    width: 100%;
    height: 100vh;
  }

  .authbg>img {
    width: 600px;
    height: 500px;
    object-fit: contain;
  }

  .container {
    max-width: 720px;
  }

  .md-width-auto {
    width: auto;
  }

  .md-col {
    flex-basis: 0;
    flex-grow: 1;
    width: 100%;
  }

  .md-col-1 {
    width: 8.333333%;
  }

  .md-col-2 {
    width: 16.666667%;
  }

  .md-col-3 {
    width: 25%;
  }

  .md-col-4 {
    width: 33.333333%;
  }

  .md-col-5 {
    width: 41.666667%;
  }

  .md-col-6 {
    width: 50%;
  }

  .md-col-7 {
    width: 58.333333%;
  }

  .md-col-8 {
    width: 66.666667%;
  }

  .md-col-9 {
    width: 75%;
  }

  .md-col-10 {
    width: 83.333333%;
  }

  .md-col-11 {
    width: 91.666667%;
  }

  .md-col-12 {
    width: 100%;
  }

  .md-col-1,
  .md-col-2,
  .md-col-3,
  .md-col-4,
  .md-col-5,
  .md-col-6,
  .md-col-7,
  .md-col-8,
  .md-col-9,
  .md-col-10,
  .md-col-11,
  .md-col-12 {
    padding: 0 20px;
  }

  .md-full-width {
    width: 100%;
  }

  .md-full-screen {
    width: 100vw;
  }

  /*utilities*/
  .md-mt-20 {
    margin-top: 20px;
  }

  .md-pl-0 {
    padding-left: 0;
  }

  .md-pr-0 {
    padding-right: 0;
  }

  .md-mr-o {
    margin-right: 0;
  }

  .md-ml-0 {
    margin-left: 0;
  }
}

@media (min-width: 1024px) {
  .container {
    max-width: 960px;
    margin: 0 auto;
  }

  .container-fluid {
    margin-left: 32px;
    margin-right: 32px;
    max-width: none;
  }

  .nav-brand {
    height: 4.375rem;
  }

  .nav>.container-fluid {
    width: 100%;
    display: flex;
    align-items: stretch;
  }

  .nav-left,
  .nav-right {
    display: flex;
    align-items: center;
  }

  .nav-right {
    margin-left: auto;
  }

  .nav-left {
    margin-right: auto;
  }

  .nav-menu {
    width: auto;
    display: flex;
    align-items: center;
  }

  .nav-link,
  .nav-item,
  .nav-brand {
    height: 4.375rem;
    display: flex;
    align-items: center;
  }

  .nav-menu-button {
    display: none;
  }

  .nav-mobile {
    width: auto;
    border-bottom: unset;
  }
}

@media (min-width: 1280px) {
  .container {
    max-width: 1140px;
    margin: 0 auto;
  }

  .container-fluid {
    margin-left: 2rem;
    margin-right: 2rem;
    max-width: none;
  }

  .nav>.container-fluid {
    width: 100%;
    display: flex;
    align-items: stretch;
  }
}
</style>
