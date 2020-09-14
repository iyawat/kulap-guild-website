<template>
<div class="wrapper">

  <section class="hero hero-border is-small no-padding">
    <div class="row title-bar">
      <br>
      <div class="columns is-vcentered is-centered is-mobile">
        <div class="column is-one-third">
          <p class="title-text"> KULAP GUILD </p>
        </div>
        <div class="column is-one-third">
          <img class="logo" src="img/guild-logo.png" />
        </div>
        <div class="column is-one-third has-text-centered">
          <a href="https://www.facebook.com/groups/neardev" target="_blank">
            <b-button id="icon-desktop" icon-pack="fab" icon-left="facebook-f" type="is-kulap" inverted rounded size="is-medium">
              Join Our Guild
            </b-button>
            <font-awesome-icon id="icon-mobile" :icon="['fab','facebook']" style="color: #FFF; height: 30px; width: 30px;" />
          </a>
        </div>
      </div>
    </div>
  </section>

  <section class="hero hero-border is-small no-padding">
    <div class="columns is-flex is-multiline is-centered is-mobile is-8 no-padding">
      <div class="column is-half-desktop is-half-tablet is-full-mobile one">
        <div class="container about-content">
          <p class="content-title"> About </p>
          <p class="content-title" style="color: #29419B;"> KULAP </p>
          <p class="content-title"> Guild </p>
          <hr class="divider" style="width: 50vw; min-width: 255px; max-width: 310px;">
          <p class="content-text"> Since 2020, we've seen the web undergoing reinvention - all centered around blockchain and data. A movement that started with Bitcoin gains momentum along with Ethereum, and eventually, spawned more and more protocols which all focusing on a better web. </p>
          <br>
          <p class="content-text"> The open web includes a vision of decentralized web - where, among other things, large corporations are not custodians of or profiting from our data, intermediaries are eliminated, and censorship is just only old school memory. The future is coming and you can be a part of it. </p>
        </div>
      </div>
      <div class="column is-half-desktop is-half-tablet is-full-mobile two">
        <img class="hero-image" src="img/hero-img.png" />
      </div>
    </div>
  </section>

  <section class="hero hero-border is-small">
    <div class="container hero-content">
      <p class="content-title"> Our </p>
      <p class="content-title" style="color: #29419B;"> Guild </p>
      <p class="content-title"> Mission </p>
      <hr class="divider">
    </div><br>
    <div class="columns is-multiline is-centered is-mobile is-8">
      <div class="column is-one-thrid-desktop is-one-third-tablet is-full-mobile service-box">
        <div class="circle"> <img src="img/img_icon_coding.png" class="service-img" /> </div><br>
        <p class="service-text-title has-text-centered"> Blockchain Developer Stimulating </p><br>
        <p class="service-text"> As we are community based environment, we can help each other to encourage members, providing technology and knowledge, becomes the motivation for members result in the quality NEAR based software, product, or even more, platform. </p>
      </div>
      <div class="column is-one-thrid-desktop is-one-third-tablet is-full-mobile service-box">
        <div class="circle"> <img src="img/img_icon_community.png" class="service-img" /> </div><br>
        <p class="service-text-title has-text-centered"> Community Establising </p><br>
        <p class="service-text"> Our guild is the aggregation of the people which primary interest is NEAR protocol and related such as React, RUST/AssemblyScript. Together, we can develop the powerful blockchain community. </p>
      </div>
      <div class="column is-one-thrid-desktop is-one-third-tablet is-full-mobile service-box">
        <div class="circle"> <img src="img/img_icon_dapp.png" class="service-img" /> </div><br>
        <p class="service-text-title has-text-centered"> DApp Development </p><br>
        <p class="service-text"> DApp could be the best illustration result of the outcome product so our community will pay primary focusing on DApp development derived from NEAR Protocol knowledge and technology. </p>
      </div>
    </div>
  </section>

  <section class="hero hero-border is-small">
    <div class="container hero-content">
      <p class="content-title"> What is </p>
      <p class="content-title" style="color: #FD5A60;"> NEAR </p>
      <p class="content-title"> Protocal </p>
      <hr class="divider" style="background: #FD5A60;">
    </div>
    <div class="columns is-multiline is-vcentered is-centered is-mobile near-column">
      <div class="column is-4-desktop is-4-tablet is-full-mobile has-text-centered">
        <img src="img/logo-near.png" />
      </div>
      <div class="column is-8-desktop is-8-tablet is-full-mobile">
        <p class="near-title"> NEAR is a decentralized application platform that is secure enough to manage high value assets like money or identity and performant enough to make them useful for everyday people, putting the power of the Open Web in their hands. </p>

      </div>
    </div>
    <div class="columns is-multiline is-centered is-mobile">
      <div class="column is-one-thrids-desktop is-one-thirds-tablet is-full-mobile service-box">
        <div class="circle-pink"> <img src="img/img_icon_build.png" class="service-img" /> </div><br>
        <p class="service-text-title has-text-centered"> Build </p><br>
        <p class="service-text"> Build decentralized applications easily as a non-blockchain developer. </p>
      </div>
      <div class="column is-one-thrids-desktop is-one-thirds-tablet is-full-mobile service-box">
        <div class="circle-pink"> <img src="img/img_icon_onboard.png" class="service-img" /> </div><br>
        <p class="service-text-title has-text-centered"> Onboard </p><br>
        <p class="service-text"> Onboard users with a smooth experience, even if they aren't familiar with crypto. </p>
      </div>
      <div class="column is-one-thrids-desktop is-one-thirds-tablet is-full-mobile service-box">
        <div class="circle-pink"> <img src="img/img_icon_scale.png" class="service-img" /> </div><br>
        <p class="service-text-title has-text-centered"> Scale </p><br>
        <p class="service-text"> Scale throughput and keep costs low regardless of how successful your app becomes. </p>
      </div>
    </div>
    <section class="has-text-centered" style="padding: 50px 0;">
      <p class="near-text"> In order for decentralized applications to make a big impact on the world, they have to be easy to build, use, and maintain even when they scale to millions of users. </p>
    </section>
    <section class="has-text-centered">
      <a href="https://near.org/" target="_blank">
        <b-button icon-pack="fas" icon-right="arrow-circle-right" type="is-pink" rounded size="is-medium">
          Go to near website
        </b-button>
      </a>
    </section>
  </section>

  <section class="hero hero-border is-small">
    <div class="container hero-content">
      <p class="content-title"> About </p>
      <p class="content-title" style="color: #29419B;"> Team </p>
      <hr class="divider">
    </div><br>
    <div class="columns is-multiline is-mobile">
      <div class="column is-half-desktop is-half-tablet is-full-mobile">
        <img class="hero-image" src="img/team2.png" />
      </div>
      <div class="column is-half-desktop is-half-tablet is-full-mobile">
        <div class="container hero-content">
          <p class="content-title" style="font-size:20px;"> Blockchain Developer Community in Thailand </p><br><br>
          <p class="content-text" style="font-size:15px; max-width: 550px; line-height: 1.5;"> We are a group of developers in Thailand interested in blockchain technology. Previously, we had another community called KatinRun that is also a blockchain developer group. But focus on the ethereum platform. </p> <br><br>
          <a href="https://www.facebook.com/groups/neardev" target="_blank">
            <b-button icon-pack="fas" icon-right="arrow-circle-right" type="is-kulap" rounded size="is-medium">
              Join Our Guild
            </b-button>
          </a>
        </div>
      </div>
    </div>
  </section>

  <section class="hero hero-border is-small">
    <div class="container hero-content">
      <p class="content-title"> Frequently Asked </p>
      <p class="content-title" style="color: #29419B;"> Questions </p>
      <hr class="divider">
    </div><br><br>
    <section style="width: 80%; margin: 0 auto;">
      <b-collapse class="card" animation="slide" v-for="(collapse, index) of collapses" :key="index" :open="isOpen == index" @open="isOpen = index">
        <div slot="trigger" slot-scope="props" class="card-header" role="button">
          <p class="card-header-title">
            {{ collapse.title }}
          </p>
          <a class="card-header-icon">
            <b-icon :icon="props.open ? 'menu-down' : 'menu-up'">
            </b-icon>
          </a>
        </div>
        <div class="card-content">
          <div class="content">
            {{ collapse.text }}
          </div>
        </div>
      </b-collapse>
    </section>
  </section>

  <div class="row flex title-bar">
    <div class="columns is-vcentered is-centered">
      <p class="content-title-white"> KULAP NEAR </p>
      <p class="content-title-white footer-content"> All rights reserved. </p>
    </div>
  </div>

</div>
</template>

<script>
export default {
  name: 'Home',
  components: {},
  data() {
    return {
      isOpen: 0,
      collapses: [{
          title: 'Do I need to be a programmer or developer to join?',
          text: `Nope, but if you want to be, you can learn how to develop blockchain apps using the Guild Academy. The guild needs all sorts of people with all sorts of diverse backgrounds and capabilities. It's when people with tech skills and people with knowledge/ideas meet and get excited that innovation sparks.`
        },
        {
          title: 'Does my Guild have to be focused only on NEAR?',
          text: `No, your Guild can be focused on specific tech stack or programming language, social sciences with a connection to the open web, or anything in between. It can be a validator community, a market-driven community or a developer community. It can be based broadly around interesting new technologies or specifically about the NEAR platform. The goal of this program is to drive interest and engagement to the open web ecosystem. The incentives will most strongly reward those guilds who have strong alignment with the NEAR ecosystem but there is no requirement that the guild be 100% focused on NEAR. As we can see it clear, this is NEAR based community, thus, we primary focus on NEAR protocol. But to be honest, from connections we gathering together, this may lead to another opportunity.`
        },
        {
          title: 'What benefits will those who join the guild get?',
          text: 'The best benefit always knowledge. Moreover, the side benefit is the connection among members in the guild. Last but not least, we may boost our community with amount of NEAR token as a bounty and activity reward.'
        }
      ]
    }
  }
}
</script>

<style lang="scss">
.container {
  width: auto;
}

.flex {
  display: -webkit-box;
  display: -moz-box;
  display: -ms-flexbox;
  display: -webkit-flex;
  display: flex;
  align-items: center;
  justify-content: center;
}

.divider {
  height: 5px;
  background: #29419B;
  margin-top: -5px;
}

.logo {
  position: absolute;
  top: -10px;
  left: 0;
  right: 0;
  margin-left: auto;
  margin-right: auto;
}

.title-bar {
  min-height: 100px;
  background-color: #29419B;
  box-shadow: 0px 7px 6px rgba(0, 0, 0, 0.25);
}

.hero {
  display: flex;
  padding-bottom: 100px;

  &.no-padding {
    padding: 0 !important;
  }
}

.title-text {
  color: #FFF;
  font-size: 45px;
  font-weight: bold;
  margin-left: 2em;
}

.about-content {
  width: 600 px;
  left: 20%;
  top: 30%;
  padding-bottom: 20%;
}

.hero-image {
  float: right;
}

.content-title {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 30px;
  color: #000000;
  margin: 0;
  display: inline;
}

.content-title-blue {
  font-family: 'Montserrat', sans-serif;
  font-style: normal;
  font-weight: 900;
  font-size: 30px;
  color: #29419B;
}

.content-title-white {
  font-style: normal;
  font-weight: 900;
  font-size: 25px;
  color: #FFF;
  text-align: center;
}

.content-text {
  font-weight: normal;
  font-size: 22px;
  line-height: 35px;
  color: #000000;
}

.service-box {
  max-width: 350px;
  margin: 20px;
}

.service-text-title {
  font-weight: bold;
  font-size: 19px;
  line-height: 35px;
  color: #000000;
}

.service-img {
  margin: 0 auto;
}

.service-text {
  margin: 0 auto;
  max-width: 300px;
  font-size: 15px;
  line-height: 22px;
  color: #000000;
}

.circle {
  width: 140px;
  height: 140px;
  background: #5578FF;
  -moz-border-radius: 70px;
  -webkit-border-radius: 70px;
  border-radius: 70px;
  margin: 0 auto;
}

.circle-pink {
  width: 90px;
  height: 90px;
  background: #FFC7C9;
  -moz-border-radius: 90px;
  -webkit-border-radius: 90px;
  border-radius: 90px;
  margin: 0 auto;
}

.near-column {
  padding: 0 100px;
}

.near-title {
  color: #000;
  max-width: 800px;
  font-size: 22px;
}

.near-text {
  color: #000;
  max-width: 600px;
  margin: 0 auto;
}

.footer-content {
  // background: #29419B;
  font-weight: 400; 
  padding-left: 30px;
}

#icon-mobile {
  display: none;
}

// Mobile
@media only screen and (max-width: 768px) {

  .flex {
    display: block;
  }

  .title-text {
    font-size: 20px;
    margin-left: -5px;
  }

  .hero-image {
    width: 100%;
  }

  .hero-content {
    padding: 0 10px;
  }

  .one {
    order: 2
  }

  .two {
    order: 1
  }

  #icon-mobile {
    display: block;
    left: 0;
    right: 0;
    margin-left: auto;
    margin-right: auto;
    border-radius: 50%;
  }

  #icon-desktop {
    display: none;
  }

  .content-title {
    font-size: 25px;
    line-height: 1.5;
  }

  .content-text {
    font-size: 15px;
    line-height: 1.5;
  }

  .about-content {
    left: 0;
    top: 0;
    margin: 0 auto;
    padding: 0 30px;
  }

  .near-column,
  .near-text,
  .columns {
    padding: 0 20px;

    &.no-padding {
      padding: 0;
      padding-bottom: 100px;
    }
  }

  .near-title {
    font-size: 15px;
  }

  .footer-content {
  padding-left: 0;
}

}

// iPad Pro
@media only screen and (min-width: 769px) and (max-width: 1408px) {
  .title-text {
    font-size: 25px;
  }

  .about-content {
    padding-bottom: 200px;
  }

  #icon-mobile {
    display: none;
  }

  #icon-desktop {
    display: block;
  }

  .content-text {
    font-size: 15px;
    line-height: 1.5;
  }
}

// Big Screen
@media only screen and (min-width: 1025px) {
  .about-content {
    padding-bottom: 300px;
  }
}
</style>
