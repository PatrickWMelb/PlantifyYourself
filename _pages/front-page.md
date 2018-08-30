---
ID: 352
post_title: Front Page
author: Jonathan Green
post_excerpt: ""
layout: page
permalink: https://plantifyourself.tk/front-page/
published: true
post_date: 2016-03-22 18:41:55
---
<!-- wp:html -->
<style>
.btn {
  display: inline-block;
  font-weight: 200;
  text-align: center;
  white-space: nowrap;
  vertical-align: middle;
  user-select: none;
  border: 1px solid transparent;
  padding: 0.375rem 0.75rem;
  font-size: 1rem;
  line-height: 1.5;
  border-radius: 0.25rem;
  transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out; }
  .btn:hover, .btn:focus {
    text-decoration: none; }
  .btn:focus, .btn.focus {
    outline: 0;
    box-shadow: 0 0 0 0.2rem rgba(18, 187, 173, 0.25); }
  .btn.disabled, .btn:disabled {
    opacity: 0.65;
    box-shadow: none; }
  .btn:not(:disabled):not(.disabled) {
    cursor: pointer; }
  .btn:not(:disabled):not(.disabled):active, .btn:not(:disabled):not(.disabled).active {
    background-image: none;
    box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125); }
    .btn:not(:disabled):not(.disabled):active:focus, .btn:not(:disabled):not(.disabled).active:focus {
      box-shadow: 0 0 0 0.2rem rgba(18, 187, 173, 0.25), inset 0 3px 5px rgba(0, 0, 0, 0.125); }

a.btn.disabled,
fieldset:disabled a.btn {
  pointer-events: none; }

.btn-primary {
  color: #fff;
  background-color: #12bbad;
  border-color: #12bbad;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.15), 0 1px 1px rgba(0, 0, 0, 0.075); }
  .btn-primary:hover {
    color: #fff;
    background-color: #0f988d;
    border-color: #0e8c82; }
  .btn-primary:focus, .btn-primary.focus {
    box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.15), 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 0 0.2rem rgba(18, 187, 173, 0.5); }
  .btn-primary.disabled, .btn-primary:disabled {
    color: #fff;
    background-color: #12bbad;
    border-color: #12bbad; }
  .btn-primary:not(:disabled):not(.disabled):active, .btn-primary:not(:disabled):not(.disabled).active,
  .show > .btn-primary.dropdown-toggle {
    color: #fff;
    background-color: #0e8c82;
    border-color: #0c8177; }
    .btn-primary:not(:disabled):not(.disabled):active:focus, .btn-primary:not(:disabled):not(.disabled).active:focus,
    .show > .btn-primary.dropdown-toggle:focus {
      box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125), 0 0 0 0.2rem rgba(18, 187, 173, 0.5); }

.btn-secondary {
  color: #fff;
  background-color: #4f70ce;
  border-color: #4f70ce;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.15), 0 1px 1px rgba(0, 0, 0, 0.075); }
  .btn-secondary:hover {
    color: #fff;
    background-color: #365ac1;
    border-color: #3355b7; }
  .btn-secondary:focus, .btn-secondary.focus {
    box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.15), 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 0 0.2rem rgba(79, 112, 206, 0.5); }
  .btn-secondary.disabled, .btn-secondary:disabled {
    color: #fff;
    background-color: #4f70ce;
    border-color: #4f70ce; }
  .btn-secondary:not(:disabled):not(.disabled):active, .btn-secondary:not(:disabled):not(.disabled).active,
  .show > .btn-secondary.dropdown-toggle {
    color: #fff;
    background-color: #3355b7;
    border-color: #3051ad; }
    .btn-secondary:not(:disabled):not(.disabled):active:focus, .btn-secondary:not(:disabled):not(.disabled).active:focus,
    .show > .btn-secondary.dropdown-toggle:focus {
      box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125), 0 0 0 0.2rem rgba(79, 112, 206, 0.5); }

.btn-success {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.15), 0 1px 1px rgba(0, 0, 0, 0.075); }
  .btn-success:hover {
    color: #fff;
    background-color: #218838;
    border-color: #1e7e34; }
  .btn-success:focus, .btn-success.focus {
    box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.15), 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 0 0.2rem rgba(40, 167, 69, 0.5); }
  .btn-success.disabled, .btn-success:disabled {
    color: #fff;
    background-color: #28a745;
    border-color: #28a745; }
  .btn-success:not(:disabled):not(.disabled):active, .btn-success:not(:disabled):not(.disabled).active,
  .show > .btn-success.dropdown-toggle {
    color: #fff;
    background-color: #1e7e34;
    border-color: #1c7430; }
    .btn-success:not(:disabled):not(.disabled):active:focus, .btn-success:not(:disabled):not(.disabled).active:focus,
    .show > .btn-success.dropdown-toggle:focus {
      box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125), 0 0 0 0.2rem rgba(40, 167, 69, 0.5); }

.btn-info {
  color: #212529;
  background-color: #ccc;
  border-color: #ccc;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.15), 0 1px 1px rgba(0, 0, 0, 0.075); }
  .btn-info:hover {
    color: #212529;
    background-color: #b9b9b9;
    border-color: #b3b3b3; }
  .btn-info:focus, .btn-info.focus {
    box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.15), 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 0 0.2rem rgba(204, 204, 204, 0.5); }
  .btn-info.disabled, .btn-info:disabled {
    color: #212529;
    background-color: #ccc;
    border-color: #ccc; }
  .btn-info:not(:disabled):not(.disabled):active, .btn-info:not(:disabled):not(.disabled).active,
  .show > .btn-info.dropdown-toggle {
    color: #212529;
    background-color: #b3b3b3;
    border-color: #acacac; }
    .btn-info:not(:disabled):not(.disabled):active:focus, .btn-info:not(:disabled):not(.disabled).active:focus,
    .show > .btn-info.dropdown-toggle:focus {
      box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125), 0 0 0 0.2rem rgba(204, 204, 204, 0.5); }

.btn-warning {
  color: #212529;
  background-color: #ffc107;
  border-color: #ffc107;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.15), 0 1px 1px rgba(0, 0, 0, 0.075); }
  .btn-warning:hover {
    color: #212529;
    background-color: #e0a800;
    border-color: #d39e00; }
  .btn-warning:focus, .btn-warning.focus {
    box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.15), 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 0 0.2rem rgba(255, 193, 7, 0.5); }
  .btn-warning.disabled, .btn-warning:disabled {
    color: #212529;
    background-color: #ffc107;
    border-color: #ffc107; }
  .btn-warning:not(:disabled):not(.disabled):active, .btn-warning:not(:disabled):not(.disabled).active,
  .show > .btn-warning.dropdown-toggle {
    color: #212529;
    background-color: #d39e00;
    border-color: #c69500; }
    .btn-warning:not(:disabled):not(.disabled):active:focus, .btn-warning:not(:disabled):not(.disabled).active:focus,
    .show > .btn-warning.dropdown-toggle:focus {
      box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125), 0 0 0 0.2rem rgba(255, 193, 7, 0.5); }

.btn-danger {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.15), 0 1px 1px rgba(0, 0, 0, 0.075); }
  .btn-danger:hover {
    color: #fff;
    background-color: #c82333;
    border-color: #bd2130; }
  .btn-danger:focus, .btn-danger.focus {
    box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.15), 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 0 0.2rem rgba(220, 53, 69, 0.5); }
  .btn-danger.disabled, .btn-danger:disabled {
    color: #fff;
    background-color: #dc3545;
    border-color: #dc3545; }
  .btn-danger:not(:disabled):not(.disabled):active, .btn-danger:not(:disabled):not(.disabled).active,
  .show > .btn-danger.dropdown-toggle {
    color: #fff;
    background-color: #bd2130;
    border-color: #b21f2d; }
    .btn-danger:not(:disabled):not(.disabled):active:focus, .btn-danger:not(:disabled):not(.disabled).active:focus,
    .show > .btn-danger.dropdown-toggle:focus {
      box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125), 0 0 0 0.2rem rgba(220, 53, 69, 0.5); }

.btn-light {
  color: #212529;
  background-color: #f3f3f3;
  border-color: #f3f3f3;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.15), 0 1px 1px rgba(0, 0, 0, 0.075); }
  .btn-light:hover {
    color: #212529;
    background-color: #e0e0e0;
    border-color: #dadada; }
  .btn-light:focus, .btn-light.focus {
    box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.15), 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 0 0.2rem rgba(243, 243, 243, 0.5); }
  .btn-light.disabled, .btn-light:disabled {
    color: #212529;
    background-color: #f3f3f3;
    border-color: #f3f3f3; }
  .btn-light:not(:disabled):not(.disabled):active, .btn-light:not(:disabled):not(.disabled).active,
  .show > .btn-light.dropdown-toggle {
    color: #212529;
    background-color: #dadada;
    border-color: lightgray; }
    .btn-light:not(:disabled):not(.disabled):active:focus, .btn-light:not(:disabled):not(.disabled).active:focus,
    .show > .btn-light.dropdown-toggle:focus {
      box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125), 0 0 0 0.2rem rgba(243, 243, 243, 0.5); }

.btn-dark {
  color: #fff;
  background-color: #151515;
  border-color: #151515;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.15), 0 1px 1px rgba(0, 0, 0, 0.075); }
  .btn-dark:hover {
    color: #fff;
    background-color: #020202;
    border-color: black; }
  .btn-dark:focus, .btn-dark.focus {
    box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.15), 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 0 0.2rem rgba(21, 21, 21, 0.5); }
  .btn-dark.disabled, .btn-dark:disabled {
    color: #fff;
    background-color: #151515;
    border-color: #151515; }
  .btn-dark:not(:disabled):not(.disabled):active, .btn-dark:not(:disabled):not(.disabled).active,
  .show > .btn-dark.dropdown-toggle {
    color: #fff;
    background-color: black;
    border-color: black; }
    .btn-dark:not(:disabled):not(.disabled):active:focus, .btn-dark:not(:disabled):not(.disabled).active:focus,
    .show > .btn-dark.dropdown-toggle:focus {
      box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125), 0 0 0 0.2rem rgba(21, 21, 21, 0.5); }

.btn-outline-primary {
  color: #12bbad;
  background-color: transparent;
  background-image: none;
  border-color: #12bbad; }
  .btn-outline-primary:hover {
    color: #fff;
    background-color: #12bbad;
    border-color: #12bbad; }
  .btn-outline-primary:focus, .btn-outline-primary.focus {
    box-shadow: 0 0 0 0.2rem rgba(18, 187, 173, 0.5); }
  .btn-outline-primary.disabled, .btn-outline-primary:disabled {
    color: #12bbad;
    background-color: transparent; }
  .btn-outline-primary:not(:disabled):not(.disabled):active, .btn-outline-primary:not(:disabled):not(.disabled).active,
  .show > .btn-outline-primary.dropdown-toggle {
    color: #fff;
    background-color: #12bbad;
    border-color: #12bbad; }
    .btn-outline-primary:not(:disabled):not(.disabled):active:focus, .btn-outline-primary:not(:disabled):not(.disabled).active:focus,
    .show > .btn-outline-primary.dropdown-toggle:focus {
      box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125), 0 0 0 0.2rem rgba(18, 187, 173, 0.5); }

.btn-outline-secondary {
  color: #4f70ce;
  background-color: transparent;
  background-image: none;
  border-color: #4f70ce; }
  .btn-outline-secondary:hover {
    color: #fff;
    background-color: #4f70ce;
    border-color: #4f70ce; }
  .btn-outline-secondary:focus, .btn-outline-secondary.focus {
    box-shadow: 0 0 0 0.2rem rgba(79, 112, 206, 0.5); }
  .btn-outline-secondary.disabled, .btn-outline-secondary:disabled {
    color: #4f70ce;
    background-color: transparent; }
  .btn-outline-secondary:not(:disabled):not(.disabled):active, .btn-outline-secondary:not(:disabled):not(.disabled).active,
  .show > .btn-outline-secondary.dropdown-toggle {
    color: #fff;
    background-color: #4f70ce;
    border-color: #4f70ce; }
    .btn-outline-secondary:not(:disabled):not(.disabled):active:focus, .btn-outline-secondary:not(:disabled):not(.disabled).active:focus,
    .show > .btn-outline-secondary.dropdown-toggle:focus {
      box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125), 0 0 0 0.2rem rgba(79, 112, 206, 0.5); }

.btn-outline-success {
  color: #28a745;
  background-color: transparent;
  background-image: none;
  border-color: #28a745; }
  .btn-outline-success:hover {
    color: #fff;
    background-color: #28a745;
    border-color: #28a745; }
  .btn-outline-success:focus, .btn-outline-success.focus {
    box-shadow: 0 0 0 0.2rem rgba(40, 167, 69, 0.5); }
  .btn-outline-success.disabled, .btn-outline-success:disabled {
    color: #28a745;
    background-color: transparent; }
  .btn-outline-success:not(:disabled):not(.disabled):active, .btn-outline-success:not(:disabled):not(.disabled).active,
  .show > .btn-outline-success.dropdown-toggle {
    color: #fff;
    background-color: #28a745;
    border-color: #28a745; }
    .btn-outline-success:not(:disabled):not(.disabled):active:focus, .btn-outline-success:not(:disabled):not(.disabled).active:focus,
    .show > .btn-outline-success.dropdown-toggle:focus {
      box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125), 0 0 0 0.2rem rgba(40, 167, 69, 0.5); }

.btn-outline-info {
  color: #ccc;
  background-color: transparent;
  background-image: none;
  border-color: #ccc; }
  .btn-outline-info:hover {
    color: #212529;
    background-color: #ccc;
    border-color: #ccc; }
  .btn-outline-info:focus, .btn-outline-info.focus {
    box-shadow: 0 0 0 0.2rem rgba(204, 204, 204, 0.5); }
  .btn-outline-info.disabled, .btn-outline-info:disabled {
    color: #ccc;
    background-color: transparent; }
  .btn-outline-info:not(:disabled):not(.disabled):active, .btn-outline-info:not(:disabled):not(.disabled).active,
  .show > .btn-outline-info.dropdown-toggle {
    color: #212529;
    background-color: #ccc;
    border-color: #ccc; }
    .btn-outline-info:not(:disabled):not(.disabled):active:focus, .btn-outline-info:not(:disabled):not(.disabled).active:focus,
    .show > .btn-outline-info.dropdown-toggle:focus {
      box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125), 0 0 0 0.2rem rgba(204, 204, 204, 0.5); }

.btn-outline-warning {
  color: #ffc107;
  background-color: transparent;
  background-image: none;
  border-color: #ffc107; }
  .btn-outline-warning:hover {
    color: #212529;
    background-color: #ffc107;
    border-color: #ffc107; }
  .btn-outline-warning:focus, .btn-outline-warning.focus {
    box-shadow: 0 0 0 0.2rem rgba(255, 193, 7, 0.5); }
  .btn-outline-warning.disabled, .btn-outline-warning:disabled {
    color: #ffc107;
    background-color: transparent; }
  .btn-outline-warning:not(:disabled):not(.disabled):active, .btn-outline-warning:not(:disabled):not(.disabled).active,
  .show > .btn-outline-warning.dropdown-toggle {
    color: #212529;
    background-color: #ffc107;
    border-color: #ffc107; }
    .btn-outline-warning:not(:disabled):not(.disabled):active:focus, .btn-outline-warning:not(:disabled):not(.disabled).active:focus,
    .show > .btn-outline-warning.dropdown-toggle:focus {
      box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125), 0 0 0 0.2rem rgba(255, 193, 7, 0.5); }

.btn-outline-danger {
  color: #dc3545;
  background-color: transparent;
  background-image: none;
  border-color: #dc3545; }
  .btn-outline-danger:hover {
    color: #fff;
    background-color: #dc3545;
    border-color: #dc3545; }
  .btn-outline-danger:focus, .btn-outline-danger.focus {
    box-shadow: 0 0 0 0.2rem rgba(220, 53, 69, 0.5); }
  .btn-outline-danger.disabled, .btn-outline-danger:disabled {
    color: #dc3545;
    background-color: transparent; }
  .btn-outline-danger:not(:disabled):not(.disabled):active, .btn-outline-danger:not(:disabled):not(.disabled).active,
  .show > .btn-outline-danger.dropdown-toggle {
    color: #fff;
    background-color: #dc3545;
    border-color: #dc3545; }
    .btn-outline-danger:not(:disabled):not(.disabled):active:focus, .btn-outline-danger:not(:disabled):not(.disabled).active:focus,
    .show > .btn-outline-danger.dropdown-toggle:focus {
      box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125), 0 0 0 0.2rem rgba(220, 53, 69, 0.5); }

.btn-outline-light {
  color: #f3f3f3;
  background-color: transparent;
  background-image: none;
  border-color: #f3f3f3; }
  .btn-outline-light:hover {
    color: #212529;
    background-color: #f3f3f3;
    border-color: #f3f3f3; }
  .btn-outline-light:focus, .btn-outline-light.focus {
    box-shadow: 0 0 0 0.2rem rgba(243, 243, 243, 0.5); }
  .btn-outline-light.disabled, .btn-outline-light:disabled {
    color: #f3f3f3;
    background-color: transparent; }
  .btn-outline-light:not(:disabled):not(.disabled):active, .btn-outline-light:not(:disabled):not(.disabled).active,
  .show > .btn-outline-light.dropdown-toggle {
    color: #212529;
    background-color: #f3f3f3;
    border-color: #f3f3f3; }
    .btn-outline-light:not(:disabled):not(.disabled):active:focus, .btn-outline-light:not(:disabled):not(.disabled).active:focus,
    .show > .btn-outline-light.dropdown-toggle:focus {
      box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125), 0 0 0 0.2rem rgba(243, 243, 243, 0.5); }

.btn-outline-dark {
  color: #151515;
  background-color: transparent;
  background-image: none;
  border-color: #151515; }
  .btn-outline-dark:hover {
    color: #fff;
    background-color: #151515;
    border-color: #151515; }
  .btn-outline-dark:focus, .btn-outline-dark.focus {
    box-shadow: 0 0 0 0.2rem rgba(21, 21, 21, 0.5); }
  .btn-outline-dark.disabled, .btn-outline-dark:disabled {
    color: #151515;
    background-color: transparent; }
  .btn-outline-dark:not(:disabled):not(.disabled):active, .btn-outline-dark:not(:disabled):not(.disabled).active,
  .show > .btn-outline-dark.dropdown-toggle {
    color: #fff;
    background-color: #151515;
    border-color: #151515; }
    .btn-outline-dark:not(:disabled):not(.disabled):active:focus, .btn-outline-dark:not(:disabled):not(.disabled).active:focus,
    .show > .btn-outline-dark.dropdown-toggle:focus {
      box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125), 0 0 0 0.2rem rgba(21, 21, 21, 0.5); }

.btn-link {
  font-weight: 200;
  color: #12bbad;
  background-color: transparent; }
  .btn-link:hover {
    color: #0b756c;
    text-decoration: underline;
    background-color: transparent;
    border-color: transparent; }
  .btn-link:focus, .btn-link.focus {
    text-decoration: underline;
    border-color: transparent;
    box-shadow: none; }
  .btn-link:disabled, .btn-link.disabled {
    color: #6c757d; }

.btn-lg, .btn-group-lg > .btn {
  padding: 0.5rem 1rem;
  font-size: 1.25rem;
  line-height: 1.5;
  border-radius: 0.3rem; }

.btn-sm, .btn-group-sm > .btn {
  padding: 0.25rem 0.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
  border-radius: 0.2rem; }

.btn-block {
  display: block;
  width: 100%; }
  .btn-block + .btn-block {
    margin-top: 0.5rem; }

input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%; }

.fade {
  opacity: 0;
  transition: opacity 0.15s linear; }
  .fade.show {
    opacity: 1; }

.collapse {
  display: none; }
  .collapse.show {
    display: block; }

tr.collapse.show {
  display: table-row; }

tbody.collapse.show {
  display: table-row-group; }

.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  transition: height 0.35s ease; }

.dropup,
.dropdown {
  position: relative; }

.dropdown-toggle::after {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 0.255em;
  vertical-align: 0.255em;
  content: "";
  border-top: 0.3em solid;
  border-right: 0.3em solid transparent;
  border-bottom: 0;
  border-left: 0.3em solid transparent; }

.dropdown-toggle:empty::after {
  margin-left: 0; }

.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 10rem;
  padding: 0.5rem 0;
  margin: 0.125rem 0 0;
  font-size: 1rem;
  color: #333;
  text-align: left;
  list-style: none;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 0.25rem;
  box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.175); }

.dropup .dropdown-menu {
  margin-top: 0;
  margin-bottom: 0.125rem; }

.dropup .dropdown-toggle::after {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 0.255em;
  vertical-align: 0.255em;
  content: "";
  border-top: 0;
  border-right: 0.3em solid transparent;
  border-bottom: 0.3em solid;
  border-left: 0.3em solid transparent; }

.dropup .dropdown-toggle:empty::after {
  margin-left: 0; }

.dropright .dropdown-menu {
  margin-top: 0;
  margin-left: 0.125rem; }

.dropright .dropdown-toggle::after {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 0.255em;
  vertical-align: 0.255em;
  content: "";
  border-top: 0.3em solid transparent;
  border-bottom: 0.3em solid transparent;
  border-left: 0.3em solid; }

.dropright .dropdown-toggle:empty::after {
  margin-left: 0; }

.dropright .dropdown-toggle::after {
  vertical-align: 0; }

.dropleft .dropdown-menu {
  margin-top: 0;
  margin-right: 0.125rem; }

.dropleft .dropdown-toggle::after {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 0.255em;
  vertical-align: 0.255em;
  content: ""; }

.dropleft .dropdown-toggle::after {
  display: none; }

.dropleft .dropdown-toggle::before {
  display: inline-block;
  width: 0;
  height: 0;
  margin-right: 0.255em;
  vertical-align: 0.255em;
  content: "";
  border-top: 0.3em solid transparent;
  border-right: 0.3em solid;
  border-bottom: 0.3em solid transparent; }

.dropleft .dropdown-toggle:empty::after {
  margin-left: 0; }

.dropleft .dropdown-toggle::before {
  vertical-align: 0; }

.dropdown-divider {
  height: 0;
  margin: 0.75rem 0;
  overflow: hidden;
  border-top: 1px solid #e9ecef; }

.dropdown-item {
  display: block;
  width: 100%;
  padding: 0.25rem 1.5rem;
  clear: both;
  font-weight: 200;
  color: #212529;
  text-align: inherit;
  white-space: nowrap;
  background-color: transparent;
  border: 0; }
  .dropdown-item:hover, .dropdown-item:focus {
    color: #16181b;
    text-decoration: none;
    background-color: #f8f9fa; }
  .dropdown-item.active, .dropdown-item:active {
    color: #fff;
    text-decoration: none;
    background-color: #12bbad; }
  .dropdown-item.disabled, .dropdown-item:disabled {
    color: #6c757d;
    background-color: transparent; }

.dropdown-menu.show {
  display: block; }

.dropdown-header {
  display: block;
  padding: 0.5rem 1.5rem;
  margin-bottom: 0;
  font-size: 0.875rem;
  color: #6c757d;
  white-space: nowrap; }

.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-flex;
  vertical-align: middle; }
  .btn-group > .btn,
  .btn-group-vertical > .btn {
    position: relative;
    flex: 0 1 auto; }
    .btn-group > .btn:hover,
    .btn-group-vertical > .btn:hover {
      z-index: 1; }
    .btn-group > .btn:focus, .btn-group > .btn:active, .btn-group > .btn.active,
    .btn-group-vertical > .btn:focus,
    .btn-group-vertical > .btn:active,
    .btn-group-vertical > .btn.active {
      z-index: 1; }
  .btn-group .btn + .btn,
  .btn-group .btn + .btn-group,
  .btn-group .btn-group + .btn,
  .btn-group .btn-group + .btn-group,
  .btn-group-vertical .btn + .btn,
  .btn-group-vertical .btn + .btn-group,
  .btn-group-vertical .btn-group + .btn,
  .btn-group-vertical .btn-group + .btn-group {
    margin-left: -1px; }

.btn-toolbar {
  display: flex;
  flex-wrap: wrap;
  justify-content: flex-start; }
  .btn-toolbar .input-group {
    width: auto; }

.btn-group > .btn:first-child {
  margin-left: 0; }

.btn-group > .btn:not(:last-child):not(.dropdown-toggle),
.btn-group > .btn-group:not(:last-child) > .btn {
  border-top-right-radius: 0;
  border-bottom-right-radius: 0; }

.btn-group > .btn:not(:first-child),
.btn-group > .btn-group:not(:first-child) > .btn {
  border-top-left-radius: 0;
  border-bottom-left-radius: 0; }

.dropdown-toggle-split {
  padding-right: 0.5625rem;
  padding-left: 0.5625rem; }
  .dropdown-toggle-split::after {
    margin-left: 0; }

.btn-sm + .dropdown-toggle-split, .btn-group-sm > .btn + .dropdown-toggle-split {
  padding-right: 0.375rem;
  padding-left: 0.375rem; }

.btn-lg + .dropdown-toggle-split, .btn-group-lg > .btn + .dropdown-toggle-split {
  padding-right: 0.75rem;
  padding-left: 0.75rem; }

.btn-group.show .dropdown-toggle {
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125); }
  .btn-group.show .dropdown-toggle.btn-link {
    box-shadow: none; }

.btn-group-vertical {
  flex-direction: column;
  align-items: flex-start;
  justify-content: center; }
  .btn-group-vertical .btn,
  .btn-group-vertical .btn-group {
    width: 100%; }
  .btn-group-vertical > .btn + .btn,
  .btn-group-vertical > .btn + .btn-group,
  .btn-group-vertical > .btn-group + .btn,
  .btn-group-vertical > .btn-group + .btn-group {
    margin-top: -1px;
    margin-left: 0; }
  .btn-group-vertical > .btn:not(:last-child):not(.dropdown-toggle),
  .btn-group-vertical > .btn-group:not(:last-child) > .btn {
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 0; }
  .btn-group-vertical > .btn:not(:first-child),
  .btn-group-vertical > .btn-group:not(:first-child) > .btn {
    border-top-left-radius: 0;
    border-top-right-radius: 0; }

.btn-group-toggle > .btn,
.btn-group-toggle > .btn-group > .btn {
  margin-bottom: 0; }
  .btn-group-toggle > .btn input[type="radio"],
  .btn-group-toggle > .btn input[type="checkbox"],
  .btn-group-toggle > .btn-group > .btn input[type="radio"],
  .btn-group-toggle > .btn-group > .btn input[type="checkbox"] {
    position: absolute;
    clip: rect(0, 0, 0, 0);
    pointer-events: none; }

.dropbtn {
    background-color: #4CAF50;
    color: white;
    padding: 16px;
    font-size: 16px;
    border: none;
}

.dropdown {
    position: relative;
    display: inline-block;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f1f1f1;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
}

.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
}

.dropdown-content a:hover {background-color: #ddd;}

.dropdown:hover .dropdown-content {display: block;}

.dropdown:hover .dropbtn {background-color: #3e8e41;}
</style>
<div class="py-5">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <h1 class="CTitle">How many nutritions you need?</h1>
        </div>
      </div>
    </div>
  </div>
  <div class="py-5">
    <div class="container">
      <div class="row">
        <div class="col-md-2">
          <p class="lead">Your Gender: </p>
        </div>
        <div class="col-md-6 ">
          <div class="dropdown">
            <button class="dropbtn"> Gender </button>
            <div class="dropdown-content">
              <a href="#">Male</a>
              <a href="#">Female</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="CTitle">
    <div class="container">
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
      </div>
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
      </div>
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
      </div>
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
      </div>
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
      </div>
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
      </div>
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
      </div>
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
      </div>
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
      </div>
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
      </div>
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
      </div>
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
      </div>
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
      </div>
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
      </div>
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
      </div>
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
        <div class="col-md-3"></div>
      </div>
    </div>
  </div>
<script>
    var mysql = require('mysql');

var con = mysql.createConnection({
  host: "35.232.215.112",
  user: "root",
  password: "1234,qwer",
  database: "VegNutr"
});

con.connect(function(err) {
  if (err) throw err;
  con.query("SELECT * FROM VegNutr", function (err, result, fields) {
    if (err) throw err;
    console.log(result);
  });
});
  </script>
<!-- /wp:html -->