<script setup>
import HomeView from "./views/HomeView.vue";
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <HomeView><router-view /></HomeView>
</template>

<style>
@font-face {
  font-family: 'proximanova_regular';
  src: url('fonts/proximanova_regular.ttf')
}

@font-face {
  font-family: 'proximanova_bold';
  src: url('fonts/proximanova_bold.otf')
}

body * {
  font-family: 'proximanova_regular';
}

body {
  margin: 0;
  padding: 0;
}

/* NAV  */


.nav {
  height: 90px;
  display: flex;
  align-items: center;
  padding-left: 100px;
  position: sticky;
  top: 0;
  background-color: #fff;
  z-index: 100;
}

.nav ul {
  display: flex;
  flex-flow: row nowrap;
  list-style: none;
  
}

.logo {
  margin-right: 40px;
}

.l-menu {
  margin-right: 410px;
}

.l-menu li{
  text-transform: uppercase;
  color: #676F73;
  margin-right: 40px;
  font-size: 18px;

}

.l-menu li:last-child {
  margin: 0;
}

.l-menu svg {
  margin-left: 4px;
  margin-bottom: 4px;
}
.r-menu {
  display: flex;
  align-items: center;
}

.r-menu li {
  font-size: 26px;
  margin-right: 40px;
}


.underline-nav hr {
  height: 2px;
  width: 1700px;
  background-color:#676f733b;
  border: none;
  margin-top: 0px;
  margin-bottom: 0px;
}

.r-menu button, .l-block button {
  background-color: #5D5FEF;
  width: 280px;
  color: white;
  font-size: 16px;
  text-transform: uppercase;
  border: none;
  height: 72.5px;
  border-radius: 6px;
  cursor: pointer;
}

/* FIRST-PAGE */

.container {
  margin-left: 100px;
  margin-right: 100px;
  display: flex;
}

.l-block {
  width: 50%;
  margin-top: 130px;
}

.container .l-block h1 {
  text-transform: uppercase;
  font-size: 85px;
  color: #263238;
  font-family: 'proximanova_bold';
  margin: 0;
}

.container .l-block p {
  font-size:32px;
  color: #676F73;
  margin-bottom: 90px;
}

.r-block {
  margin-left: 190px;
  margin-top: 70px;
  width: 50%;
}

/* SECOND-PAGE */

.container2 {
  margin-top: 150px;
  margin-left: 100px;
  margin-right: 100px;
  display: flex;
  margin-bottom: 200px;
}


.first-block {
  border-bottom: 1px solid #676F73;
  border-right: 1px solid #676F73;
  height: 600px;
  padding: 0px 40px 30px 0px;
}


.second-block {
  border-bottom: 1px solid #676F73;
  padding: 0px 40px 30px 0px;
  border-right: 1px solid #676F73;
  height: 600px;
}



.third-block {
  border-bottom: 1px solid #676F73;
  height: 600px;
  padding: 0px 40px 30px 0px;
}

.container2 h2 {
  text-transform: uppercase;
  font-size: 30px;
}
.container2 p {
  font-size: 30px;
  color: #676F73;
}

.container2 hr {
  margin-inline-start: 0;
  margin-inline-end: 0;
}

.line {
  margin-right: 40px;
  width: 33%;
}

.line hr {
  height: 1px;
  background-color: #676F73;
  margin-bottom: 30px;
  width: 490px;
  border: none;
}

/* TECHNOLOGY */

.container3 {
  margin-left: 100px;
  margin-right: 100px;
  margin-bottom: 100px;
}

.container3 h1 {
  text-transform: uppercase;
  font-size: 57px;
  color: #263238;
  margin-bottom: 50px;
}

.technology-block {
  display: flex;
}

.technology-one, .technology-two, .technology-three {
  width: 33%;
}

.card {
  display: flex;
  align-items: center;
  margin-bottom: 90px;
  margin-right: 50px;
}


.card svg {
  margin-right: 80px;
}

.card h2 {
  margin: 0;
  font-size: 45px;
  color: #263238;
}

.card p {
  margin: 0;
  font-size: 25px;
  color: #676F73;
}


/* POSSIBILITIES */

.container4 {
  margin-left: 100px;
  margin-right: 100px;
  margin-bottom: 200px;
}

.container4 h1 {
  text-transform: uppercase;
  font-size: 57px;
  color: #263238;
  margin-bottom: 50px;
}

.blocks-possib {
  display: flex;
}

.first-possib {
  width: 33%;
}

.second-possib {
  width: 33%;
}

.third-possib {
  width: 33%;
}



.container4 h2 {
  color: #263238;
  text-transform: uppercase;
  font-size: 30px;
}

.container4 p {
  font-size: 28px;
  width: 500px;
  color: #676F73;
}

.possibility {
  height: 592px;
}

.possibility h1 {
  color: #5457F5;
}
.numbers1 hr {
  position: absolute;
  width: 400px;
  top: 2974px;
  left: 200px;
  background-color: #5457F5;
  height: 3px;
  border: none;
}

.numbers2 hr {
  position: absolute;
  width: 400px;
  top: 2974px;
  left: 760px;
  background-color: #5457F5;
  height: 3px;
  border: none;
}

.numbers3 hr {
  position: absolute;
  width: 400px;
  top: 2974px;
  left: 1320px;
  background-color: #5457F5;
  height: 3px;
  border: none;
}

.numbers4 hr {
  position: absolute;
  width: 400px;
  top: 3604px;
  left: 200px;
  background-color: #5457F5;
  height: 3px;
  border: none;
}

.numbers5 hr {
  position: absolute;
  width: 400px;
  top: 3604px;
  left: 760px;
  background-color: #5457F5;
  height: 3px;
  border: none;
}

.numbers6 hr {
  position: absolute;
  width: 400px;
  top: 3604px;
  left: 1320px;
  background-color: #5457F5;
  height: 3px;
  border: none;
}

.numbers7 hr {
  position: absolute;
  width: 400px;
  top: 4235px;
  left: 1320px;
  background-color: #5457F5;
  height: 3px;
  border: none;
}

.numbers8 hr {
  position: absolute;
  width: 400px;
  top: 4235px;
  left: 760px;
  background-color: #5457F5;
  height: 3px;
  border: none;
}

.numbers9 hr {
  position: absolute;
  width: 400px;
  top: 4235px;
  left: 200px;
  background-color: #5457F5;
  height: 3px;
  border: none;
}


/* SUBCRIPTION PACKAGES */

.container5 {
  margin-left: 100px;
  margin-right: 100px;
  margin-bottom: 100px;
}

.container5 .header-text h1 {
  text-transform: uppercase;
  font-size: 57px;
  color: #263238;
  margin-bottom: 50px;
}

.header-text {
  justify-content: space-between;
  display: flex;
}

.header-text p {
  color: #676F73;
  font-size: 30px;
  width: 700px;
  margin-top: 45px;
}

.packages-blocks {
  margin-top: 40px;
  display: flex;
}

.p-block-one {
  width: 33%;
  margin-right: 30px;
  height: 1350px;
  border: 1px solid #263238;
  padding: 80px 75px 80px 75px;
  border-radius: 5px;
}

.p-block-two {
  width: 33%;
  margin-right: 30px;
  height: 1350px;
  border: 1px solid #263238;
  padding: 80px 75px 80px 75px;
  border-radius: 5px;
}

.p-block-three {
  width: 33%;
  height: 1350px;
  border: 1px solid #263238;
  padding: 80px 75px 80px 75px;
  border-radius: 5px;
}

.p-block-one h1, .p-block-two h1, .p-block-three h1 {
  text-transform: uppercase;
  font-size: 60px;
  color: #263238;
}

.p-block-one h4, .p-block-two h4, .p-block-three h4 {
  text-transform: uppercase;
  font-size: 29px;
  color: #263238;
}

.categories p, .categories-light p {
  margin-left: 50px;
  font-size: 23px;
}

.categories p {
  color: #263238;
}

.categories, .categories-light {
  align-items: center;
  display: flex;
}

.categories-light {
  color: #A8ADAF;
}

.line-third-block-1 hr{
  margin-top: 40px;
  margin-bottom: 40px;
  width: 340px;
  color: #BABDBF;
}

.line-third-block-2 hr {
  margin-top: 40px;
  height: 2px;
  border: none;
  background-color: #263238;
}

.p-block-three h2 {
  color: #5759F3;
  font-size: 77px;
  font-weight: bold;
}


.p-block-one .line-third-block-2 hr, .p-block-two .line-third-block-2 hr{
  margin-top: 280px;
}


.p-block-one h2, .p-block-two h2 {
  color: #263238;
  font-size: 77px;
  font-weight: bold;
}


/* PROJECTS */

.container6 {
  margin-top: 200px;
  margin-left: 100px;
  margin-right: 100px;
  margin-bottom: 100px;
}

.container6 h1 {
  text-transform: uppercase;
  font-size: 57px;
  color: #263238;
  margin-bottom: 50px;
}

.project-blocks {
  display: flex;
}

.project-one {
  width: 33%;
  margin-right: 40px;
}

.project-two {
  width: 33%;
  margin-right: 40px;
}

.project-three {
  width: 33%;
}

.project-photo {
  border-radius: 5px;
  border: 1px solid #000;
  width: 540px;
  height: 440px;
  justify-content: center;
  align-items: center;
  display: flex;
}

.project-photo img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}

.project-photo .p-button-one {
  position: absolute;
  left: 7%;
  top: 7547px;
}

.project-photo .p-button-two {
  position: absolute;
  left: 37.4%;
  top: 7547px;
}


.project-photo .p-button-three {
  position: absolute;
  left: 68%;
  top: 7547px;
}

.project-photo button {
  border: none;
  background-color: #E6E6E6;
  color: #676F73;
  padding: 6px 30px 6px 30px;
  font-size: 17px;
  border-radius: 6px;
  cursor: pointer;
}

.container6 h4 {
  color: #263238;
  font-size: 35px;
}

.center-button {
  margin-top: 50px;
  display: block;
  margin-left: auto;
  margin-right: auto;
  border: solid 2px #5D5FEF;
  padding: 30px 100px 30px 100px;
  background-color: #fff;
  border-radius: 5px;
  text-transform: uppercase;
  font-size: 25px;
  font-weight: bold;
  cursor: pointer;
}

/* FOOTER */

.color-wall {
  align-items: center;
  display: flex;
  width: 100%;
  height: 350px;
  background-color: #5457F5;
}

.color-wall h1 {
  text-transform: uppercase;
  color:#fff;
  font-size: 80px;
  margin-left: 200px;
  margin-right: 450px;
}

.footer-blocks {
  display: flex;
  margin-top: 60px;
}

.f-block-one {
  width: 40%;
}

.f-block-two {
  width: 20%;
}

.f-block-three {
  width: 20%;
}

.f-block-four {
  width: 20%;
}

.f-block-one svg {
  margin-left: 90px;
}
.footer-blocks h3 {
  font-size: 23px;
  color: #263238;
  text-transform: uppercase;
}

.footer-blocks p {
  font-size: 18px;
  color: #676F73;
}

.footer-bottom hr {
  height: 1px;
  background-color: #00000026;
  width: 1720px;
  margin-top: 100px;
  border: none;
}

.footer-info {
  height: 60px;
}


.footer-nav {
  height: 90px;
  display: flex;
  align-items: center;
  margin-left: 50px;
  justify-content: space-between;
}


.footer-nav ul {
  display: flex;
  flex-flow: row nowrap;
  list-style: none;
}

.footer-nav li {
  margin-right: 100px;
  color: #676F73;
  font-size: 17px;
}

.r-footer-bottom {
  height: 90px;
  align-items: center;
  display: flex;
}

.r-footer-bottom {
  margin-right: 110px;
}

.r-footer-bottom svg {
  margin-left: 50px;
}


</style>
