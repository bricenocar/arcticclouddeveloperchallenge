<template>
  <div>
    <div class="container-fluid">
      <div v-responsive="['hidden-all', 'xl']" class="legoLeft">
        <img class="legoleftpicture" src="../assets/images/biglego.svg" />
      </div>
      <div class="row quickSummary">
        <div class="container">
          <div class="main-section-top">
            <div class="row logo-container">
              <img class="logotop" src="../assets/images/logo-2021.svg" />
            </div>
            <div class="row legodivider">
              <img class="legodividerimg" src="../assets/images/legoline.svg" />
            </div>
            <div class="row legodivider">
              <img
                class="legodividerimg"
                src="../assets/images/texto-home.svg"
              />
            </div>
            <div class="row legodivider">
              <p class="event-date">February 04th-07th 2021</p>
            </div>
            <div class="row legodivider">
              <a
                class="registerbuttonlink"
                href="https://forms.office.com/Pages/ResponsePage.aspx?id=-bM9M7wUjUOYLzc2t8hWPlPngU499LtNtryHiN0d-t5UQU4wVlJCTlQ2MVY2Q1VLVDUxVDhTQ1hPWSQlQCN0PWcu"
                target="_blank"
              >
                <div class="registerbutton">REGISTER TODAY</div>
              </a>
            </div>
            <div class="row separator"></div>
            <div class="legoyellow">
              <img class="brikk" src="../assets/images/legoyellow.svg" />
            </div>
            <div class="legoredleft">
              <img class="brikk" src="../assets/images/legoredleft.svg" />
            </div>
            <div class="legoblue">
              <img class="brikk" src="../assets/images/legoblue.svg" />
            </div>
            <div class="legoredright">
              <img class="brikk" src="../assets/images/legoredright.svg" />
            </div>
          </div>
        </div>
      </div>
      <div class="row Categories">
        <div class="categoriesHeader">
          <div class="categoriesIcon">
            <img
              class="categoryIcon"
              src="../assets/images/Icon-categories.svg"
            />
          </div>
          <div class="categoriesTitle">
            <h1>Categories</h1>
            <p>(Subject to change)</p>
          </div>
        </div>
        <div class="container">
          <div class="categoriesContent">
            <div class="row">
              <div class="categoryCard col-md-4">
                <div class="categoryContent">
                  <div class="categoryPicture">
                    <img
                      class="categoryPictureImg"
                      src="../assets/images/Mario.svg"
                    />
                  </div>
                  <div class="categoryTitle">
                    <h2>LEGO Super Mario power</h2>
                  </div>
                  <div class="categoryDescription">
                    <p>
                      Power users love tools and flexibility, so why not show
                      them some by using tools available to the average office
                      and line worker out there. More power less code! Power
                      Automate, Power Apps, Power BI, Power Virtual Agent
                    </p>
                  </div>
                </div>
              </div>
              <div class="categoryCard col-md-4">
                <div class="categoryContent">
                  <div class="categoryPicture">
                    <img
                      class="categoryPictureImg"
                      src="../assets/images/HarryPotter.svg"
                    />
                  </div>
                  <div class="categoryTitle">
                    <h2>LEGO Harry Potter</h2>
                  </div>
                  <div class="categoryDescription">
                    <p>
                      Everything is so pretty, I can't take my eyes away!
                      Applications are not all about functionality, they have to
                      look pretty as well - why else have design manuals? Glossy
                      pixels, User interactive, Responsivenes
                    </p>
                  </div>
                </div>
              </div>
              <div class="categoryCard col-md-4">
                <div class="categoryContent">
                  <div class="categoryPicture">
                    <img
                      class="categoryPictureImg"
                      src="../assets/images/BOOST.svg"
                    />
                  </div>
                  <div class="categoryTitle">
                    <h2>LEGO MINDSTORMS</h2>
                  </div>
                  <div class="categoryDescription">
                    <p>
                      All the tiny things, connected and online. Bring your IoT
                      to the science fair! Azure, IoT, DevOps
                    </p>
                  </div>
                </div>
              </div>
              <div class="categoryCard col-md-4">
                <div class="categoryContent">
                  <div class="categoryPicture">
                    <img
                      class="categoryPictureImg"
                      src="../assets/images/StarWars.svg"
                    />
                  </div>
                  <div class="categoryTitle">
                    <h2>LEGO Star Wars</h2>
                  </div>
                  <div class="categoryDescription">
                    <p>
                      Cash is king, and nothing says cash like great business
                      value. Usable solutions, Feasable Ideas, Real world
                      scenarios
                    </p>
                  </div>
                </div>
              </div>
              <div class="categoryCard col-md-4">
                <div class="categoryContent">
                  <div class="categoryPicture">
                    <img
                      class="categoryPictureImg"
                      src="../assets/images/Ninjago.svg"
                    />
                  </div>
                  <div class="categoryTitle">
                    <h2>NINJAGO fortress</h2>
                  </div>
                  <div class="categoryDescription">
                    <p>
                      Secure your solutions, dont let Loki get past your gates!
                      Keyvaults, GDPR, Secured Services
                    </p>
                  </div>
                </div>
              </div>
              <div class="categoryCard col-md-4">
                <div class="categoryContent">
                  <div class="categoryPicture">
                    <img
                      class="categoryPictureImg"
                      src="../assets/images/Marvel.svg"
                    />
                  </div>
                  <div class="categoryTitle">
                    <h2>LEGO Marvel spirit</h2>
                  </div>
                  <div class="categoryDescription">
                    <p>
                      Be a happy camper, spread the love, show your amazing team
                      spirit! Help others in need, decorations, possitive vibes
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="row theAward">
        <div class="categoriesHeader">
          <div class="categoriesIcon">
            <img class="categoryIcon" src="../assets/images/icon-award.svg" />
          </div>
          <div class="theAwardTitle">
            <h1>The award</h1>
            <p>The winning team get to take home the ANTLERS to keep</p>
            <p>until next challenge</p>
            <br />
            <p>And all the glory they can carry</p>
          </div>
        </div>
      </div>
      <div class="row judges">
        <div class="container">
          <div class="judgesTitle darktext">
            <h1>Judges</h1>
          </div>
          <div class="row legodivider">
            <img class="legodividerimg2" src="../assets/images/legoline.svg" />
          </div>
        </div>
        <div class="judgesContent">
          <div class="row">
            <div class="judgeCard col-md-4">
              <div class="judgeContent">
                <div class="judgePicture">
                  <img
                    class="judgePictureImg"
                    src="../assets/images/judge-1.svg"
                  />
                </div>
                <div class="judgeTitle">
                  <h2>TBA</h2>
                </div>
                <div class="judgeDescription">
                  <p>Creative engineer with excellent communication skills</p>
                </div>
              </div>
            </div>
            <div class="judgeCard col-md-4">
              <div class="judgeContent">
                <div class="judgePicture">
                  <img
                    class="judgePictureImg"
                    src="../assets/images/judge-2.svg"
                  />
                </div>
                <div class="judgeTitle">
                  <h2>TBA</h2>
                </div>
                <div class="judgeDescription">
                  <p>Creative engineer with excellent communication skills</p>
                </div>
              </div>
            </div>
            <div class="judgeCard col-md-4">
              <div class="judgeContent">
                <div class="judgePicture">
                  <img
                    class="judgePictureImg"
                    src="../assets/images/judge-3.svg"
                  />
                </div>
                <div class="judgeTitle">
                  <h2>TBA</h2>
                </div>
                <div class="judgeDescription">
                  <p>Creative engineer with excellent communication skills</p>
                </div>
              </div>
            </div>
            <div class="judgeCard col-md-4">
              <div class="judgeContent">
                <div class="judgePicture">
                  <img
                    class="judgePictureImg"
                    src="../assets/images/judge-5.svg"
                  />
                </div>
                <div class="judgeTitle">
                  <h2>TBA</h2>
                </div>
                <div class="judgeDescription">
                  <p>Creative engineer with excellent communication skills</p>
                </div>
              </div>
            </div>
            <div class="judgeCard col-md-4">
              <div class="judgeContent">
                <div class="judgePicture">
                  <img
                    class="judgePictureImg"
                    src="../assets/images/judge-6.svg"
                  />
                </div>
                <div class="judgeTitle">
                  <h2>TBA</h2>
                </div>
                <div class="judgeDescription">
                  <p>Creative engineer with excellent communication skills</p>
                </div>
              </div>
            </div>
            <div class="judgeCard col-md-4">
              <div class="judgeContent">
                <div class="judgePicture">
                  <img
                    class="judgePictureImg"
                    src="../assets/images/judge-7.svg"
                  />
                </div>
                <div class="judgeTitle">
                  <h2>TBA</h2>
                </div>
                <div class="judgeDescription">
                  <p>Creative engineer with excellent communication skills</p>
                </div>
              </div>
            </div>
          </div>
          <div class="row separator"></div>
        </div>
      </div>
      <div class="row thePriceToPay">
        <div class="container thePriceToPayContainer">
          <div class="thePriceToPayHeader">
            <div class="thePriceToPayIcon">
              <img
                class="thePriceToPayIconImg"
                src="../assets/images/icon-bilette.svg"
              />
            </div>
          </div>
          <div class="thePriceToPayContent">
            <div class="thePriceToPayTitle">
              <h1>Tickets</h1>
            </div>
            <div class="thePriceToPayAmount">
              <h1>10.000 NOK</h1>
              <p>excluding VAT</p>
            </div>
            <div class="thePriceToPayIncludes">
              <ul>
                <li>
                  <p>Challenge Participants Pass</p>
                </li>
                <li>
                  <p>Three nights in single bedroom at onsite hotel</p>
                </li>
                <li>
                  <p>Breakfast Friday, Saturday and Sunday</p>
                </li>
                <li>
                  <p>Lunch, coffee and small treats for the full duration</p>
                </li>
                <li>
                  <p>Geekfood Thursday</p>
                </li>
                <li>
                  <p>Three course dinner Friday</p>
                </li>
                <li>
                  <p>Banquet dinner Saturday</p>
                </li>
                <li>
                  <p>Subsidized CloudPints</p>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="row theCampSite">
        <div class="container theCampSiteContainer">
          <div class="theCampSiteHeader">
            <div class="theCampSiteIconContainer">
              <img
                class="theCampSiteIcon"
                src="../assets/images/icon-campsite.svg"
              />
            </div>
            <div class="theCampSiteTitle">
              <h1>The campsite</h1>
              <p>
                Venue is the venerable Voksenåsen Hotel, located in the hills
                surrounding Oslo.
              </p>
              <p>
                We encourage all participants to stay at the hotel for the
                event.
              </p>
              <p>
                We will handle room bookings, and as you see from the conference
                fee most of what you'll need is covered so you can focus on
                waging the ultimate cloud battle.
              </p>
              <div class="theCampSiteFooter">
                <img
                  class="theCampSiteIcon"
                  src="../assets/images/logo-voksenaasen.svg"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="theLocation">
      <gmaps-map :options="mapOptions">
        <gmaps-marker :position="{ lat: 59.96, lng: 10.665 }" />
      </gmaps-map>
    </div>
  </div>
</template>

<script>
import { gmapsMap, gmapsMarker } from "x5-gmaps";
export default {
  name: "Home",
  methods: {
    track() {
      this.$ga.page("/");
    },
  },
  components: { gmapsMap, gmapsMarker },
  data: () => ({
    mapOptions: {
      center: { lat: 59.96, lng: 10.665 },
      zoom: 12,
    },
  }),
};
</script>
<style>
.sponsacdcheader {
  width: 100%;
  margin-top: 50px;
}
.sponsacdcTitle h1 {
  color: #27343c;
  font-size: 40pt;
  font-weight: bold;
}
.sponsacdcContent {
  width: 100%;
}
.theLocation {
  width: 100%;
  height: 400px;
  background-color: grey;
}
.main-section-top {
  max-width: 678px;
  margin: auto;
}
.legoLeft {
  position: absolute;
  left: -5%;
}
.logotop {
  margin: auto;
}
.legodividerimg {
  width: 100%;
  margin: auto;
}
.slogan-top {
  margin-top: -10%;
  font-size: 105pt;
  font-weight: 200;
  margin-bottom: -10%;
  justify-content: center;
}
.slogan-bottom {
  font-size: 140pt;
  font-weight: bold;
  margin-bottom: -5%;
  justify-content: center;
}
.registerbutton {
  color: white;
  background-color: rgba(255, 255, 255, 0.2);
  border-radius: 6pt;
  padding: 1em;
  border: white 3pt solid;
  font-family: "Open Sans";
  font-weight: bold;
  margin-top: 3em;
}
.legoleftpicture {
  max-width: 450px;
}
.legodivider {
  margin: auto;
  margin-top: 5%;
  margin-bottom: 5%;
}
.quickSummary {
  background-image: linear-gradient(to right, black, rgb(73, 71, 67));
  background-size: cover;
  height: 40%;
  padding-top: 40px;
  padding-bottom: 40px;
}
.quickSummary .container {
  padding-top: 2em;
}
.quickSummary .event-title {
  font-size: 55px;
  font-weight: 500;
  line-height: 1.2;
}
.quickSummary .event-date {
  font-size: 30px;
  font-weight: 500;
  line-height: 1.2;
  color: #ffc800;
  text-align: right;
  width: 100%;
}
.registerbuttonlink {
  width: 100%;
}
.rectangle {
  border: solid 10px;
  margin-top: 100px;
  margin-bottom: 100px;
  padding-bottom: 90px;
}
.quickSummary h1 {
  padding-bottom: 15px;
}
.quickSummary h3 {
  color: white;
}
.quickSummary p {
  color: black;
  font-weight: 900;
}
.divider {
  border: 1px solid white;
  width: 70%;
  margin: auto;
  margin-top: 5%;
  margin-bottom: 5%;
}
.dragonHeadLeft {
  float: left;
  width: 85px;
  height: 65px;
  background: url("../assets/images/dragenhead_white_trans.png") no-repeat
    center;
  margin-top: -44px;
  margin-left: -61px;
}
.dragonHeadRight {
  float: right;
  width: 85px;
  height: 65px;
  background: url("../assets/images/dragenhead_right_white_trans.png") no-repeat
    center;
  margin-top: -50px;
  margin-right: -56px;
}
.logo1Rect {
  height: 20%;
  width: 45%;
  padding-top: 70px;
}

.theAward {
  background: white;
  height: 30%;
  padding-top: 15vh;
  margin-bottom: 15vh;
}
.antlersStraight {
  height: 65px;
  background: url("../assets/images/antlers_dark_trans.png") no-repeat center;
  margin-bottom: -9px;
}
.antlersScewed {
  height: 65px;
  background: url("../assets/images/antlers_dark_trans.png") no-repeat center;
  transform: rotate(180deg);
  margin-left: 35px;
  margin-top: -18px;
}
.antlersDivider {
  border: 1px solid #27343c;
  width: 100%;
  margin-bottom: 10px;
}
.theAwardTitle {
  color: #27343c;
  font-size: 72pt;
  text-align: left;
  font-weight: bold;
}
.theAwardContent {
  margin-top: 2vh;
  color: #6d7c90;
  font-size: 15pt;
  margin-bottom: 80px;
  text-align: left;
}
.theAwardContent p {
  margin: 0;
}
.Categories {
  background: lightgray;
  background: url(../assets/images/background-legos.svg) no-repeat center;
  height: 30%;
  padding-top: 15vh;
  flex-direction: column;
}
.categoriesHeader {
  display: flex;
  width: 60%;
  margin: auto;
}
.categoriesHeader h1 {
  color: black;
  text-align: left;
  font-size: 50pt;
  font-weight: bold;
}
.categoriesHeader p {
  color: #6d7c90;
  text-align: left;
  font-size: 15pt;
}
.categoryIcon {
  margin-right: 2em;
}
.categoriesTitle {
  display: flex;
  flex-direction: column;
}
.categoriesContent {
  color: black;
  font-size: 25px;
  background-color: white;
}
.categoryCard {
  padding: 1em 2em;
}
.categoryContent {
  background-color: white;
  height: 100%;
}
.categoryPicture {
  width: 100%;
}
.categoryPictureImg {
  margin-bottom: 15px;
  width: 315px;
  height: 315px;
  padding: 25px;
}
.categoryTitle {
  font-size: 35pt;
  color: black;
  margin: 0px 1.75vw;
}
.categoryTitle h2 {
  font-weight: bold;
}
.categoryDescription {
  font-size: 12pt;
  color: #6d7c90;
  margin: 0px 1.75vw;
}
.categoriesCatTitle {
  text-align: left;
  color: white;
  font-size: 30px;
  font-weight: bold;
  margin-bottom: 15px;
  font-family: "Roboto Condensed", Georgia, Times, serif;
}
.thePriceToPay {
  background: lightgray;
  background: url(../assets/images/background-graa.svg) no-repeat center;
  height: 30%;
  padding-top: 15vh;
}
.thePriceToPayContainer {
  background: white;
  margin-top: 15vh;
  display: flex;
}
.theCampSiteContainer {
  background: white;
  margin-top: 15vh;
  display: flex;
}
.thePriceToPayHeader {
  display: flex;
}
.thePriceToPayIcon {
  margin-right: 2em;
}
.thePriceToPayImg {
  margin-bottom: 15px;
  width: 315px;
  height: 315px;
  padding: 25px;
}
.thePriceToPayTitle h1 {
  color: black;
  text-align: left;
  font-size: 50pt;
  font-weight: bold;
}
.thePriceToPayAmount {
  padding: 20px 10px;
  border: 3px solid black;
}
.thePriceToPayAmount h1 {
  color: black;
  text-align: left;
  font-size: 50pt;
  font-weight: bold;
}
.thePriceToPayAmount p {
  color: black;
  text-align: left;
  font-size: 12pt;
  font-weight: bold;
}
.thePriceToPayIncludes {
  margin-top: 10vh;
}
.thePriceToPayIncludes > ul > li {
  text-align: left;
  color: black;
  font-size: 12pt;
}
.thePriceToPayContent {
  background: white;
  flex-direction: column;
}
.judges {
  background: #2a2d35;
}
.judgesTitle {
  margin-top: 30px;
}
.judgesTitle h1 {
  color: white;
  font-size: 45px;
  font-weight: bolder;
  margin-bottom: 30px;
}
.judgesContent {
  color: white;
  font-size: 25px;
  margin-top: 5%;
  width: 80%;
  margin: auto;
}
.legodividerimg2 {
  width: 80%;
  margin: auto;
}
.darkenoverlay {
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5);
}
.judgeFrame {
  background: url("../assets/images/woodframe.png") no-repeat;
  padding: 10px 5px 5px 10px;
}
.judgeCard {
  padding: 1em 2em;
}
.judgeContent {
  height: 100%;
  padding: 0 20px;
}
.judgePicture {
  margin-bottom: 15px;
  width: 250px;
  margin: auto;
  padding: 30px;
}
.judgePictureImg {
  margin-bottom: 15px;
  width: 100%;
}
.judgeTitle {
  color: white;
  font-size: 35px;
  margin-bottom: 15px;
}
.judgeDescription {
  font-size: 12pt;
  color: #6d7c90;
  margin: 0px 1.75vw;
}
.darktext {
  color: #fff;
}
.bottomspacing {
  margin-bottom: 3em;
}
.theCampSite {
  background: white;
  padding-top: 15vh;
  flex-direction: column;
  padding-bottom: 15vh;
}
.theCampSiteHeader {
  display: flex;
  width: 60%;
  margin: auto;
}
.theCampSiteHeader h1 {
  color: black;
  text-align: left;
  font-size: 50pt;
  font-weight: bold;
}
.theCampSiteHeader p {
  color: #6d7c90;
  text-align: left;
  font-size: 15pt;
}
.theCampSiteFooter {
  display: flex;
}
.theCampSiteIcon {
  margin-right: 2em;
}
.theCampSiteTitle {
  display: flex;
  flex-direction: column;
}
.theCampSiteContent {
  color: black;
  font-size: 25px;
  background-color: white;
}
.antlersStraightWhite {
  height: 71px;
  background: url("../assets/images/antlers_allwhite_trans.png") no-repeat
    center;
  margin-bottom: -9px;
}
.antlersScewedWhite {
  height: 69px;
  background: url("../assets/images/antlers_allwhite_trans.png") no-repeat
    center;
  transform: rotate(180deg);
  margin-left: 35px;
  margin-top: -18px;
}
.antlersDividerWhite {
  border: 1px solid white;
  width: 100%;
  margin-bottom: 10px;
}
.theCampsiteTitle {
  color: white;
  font-size: 2.5rem;
}
.theCampSiteContent {
  margin-top: 80px;
  color: white;
  font-size: 25px;
  text-align: left;
  text-shadow: 1px 1px #27343c;
}
.theCampsiteSubTitle {
  color: white;
  font-size: 30px;
  margin-bottom: 15px;
  font-family: "Roboto Condensed", Georgia, Times, serif;
}
.sponsorSilverLogo {
  max-width: 200px;
  padding-top: 25px;
  padding-bottom: 25px;
}
.sponsorGoldLogo {
  max-width: 300px;
}
.sponsorGoldContainer {
  margin-bottom: 40px;
  margin-top: 60px;
}

.legoyellow {
  overflow-x: hidden;
  position: absolute;
  left: 80vw;
  top: 70vh;
}

.legoredleft {
  overflow-x: hidden;
  position: absolute;
  left: 25%;
  top: 79vh;
}

.legoblue {
  overflow-x: hidden;
  position: absolute;
  left: 65vw;
  top: 84vh;
}

.legoredright {
  overflow-x: hidden;
  position: absolute;
  left: 88vw;
  top: 90vh;
}

.separator {
  height: 10vh;
}

.line-style {
  height: 10%;
}

/* ----------- iPhone 6, 6S, 7 and 8 ----------- */
@media only screen and (min-device-width: 375px) and (max-device-width: 667px) and (-webkit-min-device-pixel-ratio: 2) {
  .main-section-top {
    max-width: 650px;
    margin: auto;
  }
  .logotop {
    max-width: 80%;
  }
  .legodividerimg {
    width: 80%;
  }
  .legodivider {
    margin: auto;
    margin-top: 0;
    margin-bottom: 0;
  }
  .slogan-top {
    font-size: 4em;
  }
  .slogan-bottom {
    font-size: 6em;
  }
  .quickSummary .event-date {
    margin: auto;
    width: 80%;
  }
  .registerbuttonlink {
    margin: auto;
    width: 80%;
  }
  .brikk {
    max-width: 35vw;
  }
  .legoredleft {
    position: absolute;
    left: 0;
    top: 120vh;
  }
  .legoyellow {
    position: absolute;
    right: 0;
    top: 115vh;
  }
  .legoblue {
    position: absolute;
    left: 60vw;
    top: 127vh;
  }
  .legoredright {
    display: none;
  }
  .categoriesHeader {
    width: 90%;
  }
  .categoriesContent {
    background-color: transparent;
  }
  .categoryIcon {
    margin-right: 1em;
  }
  .categoriesTitle h1 {
    font-size: 35pt;
  }
  .categoriesTitle p {
    font-size: 12pt;
  }
  .theAwardTitle h1 {
    font-size: 35pt;
  }
  .theAwardTitle p {
    font-size: 12pt;
  }
  .thePriceToPayTitle h1 {
    font-size: 35pt;
  }
  .thePriceToPayTitle p {
    font-size: 12pt;
  }
  .thePriceToPayAmount h1 {
    font-size: 35pt;
  }
  .thePriceToPayAmount p {
    font-size: 12pt;
  }
  .thePriceToPayIncludes {
    margin-top: 10vh;
  }
  .thePriceToPayIncludes > ul > li {
    text-align: left;
    color: black;
    font-size: 12pt;
  }
  .theCampSiteTitle h1 {
    font-size: 35pt;
  }
  .theCampSiteTitle p {
    font-size: 12pt;
  }
  .theCampSiteHeader {
    display: flex;
    width: 100%;
  }
  .theCampSiteIcon {
    max-width: 200px;
  }
  .categoryTitle {
    margin: 0px 10vw;
  }
  .categoryDescription {
    margin: 0px 10vw;
  }
  .dragonHeadLeft {
    visibility: hidden;
  }
  .dragonHeadRight {
    visibility: hidden;
  }
  .rectangle {
    border: solid 5px;
  }
  .logo2 {
    height: 10px;
    width: 200px;
  }
  .theAward {
    padding-top: 70px;
  }
  .quickSummary {
    padding-top: 0;
  }
  .theAwardTitle {
    font-size: 2.5rem;
  }
  .thePriceToPayTitle {
    font-size: 2.5rem;
  }
}

/* Portrait and Landscape */
@media only screen and (min-device-width: 920px) and (max-device-width: 1600px) {
  .legoyellow {
    overflow-x: hidden;
    position: absolute;
    left: 80vw;
    top: 110vh;
  }

  .legoredleft {
    overflow-x: hidden;
    position: absolute;
    left: 25%;
    top: 119vh;
  }

  .legoblue {
    overflow-x: hidden;
    position: absolute;
    left: 65vw;
    top: 124vh;
  }

  .legoredright {
    overflow-x: hidden;
    position: absolute;
    left: 88vw;
    top: 130vh;
  }
}

/* Portrait and Landscape */
@media only screen and (min-device-width: 414px) and (max-device-width: 736px) and (-webkit-min-device-pixel-ratio: 3) {
  .dragonHeadLeft {
    visibility: hidden;
  }
  .dragonHeadRight {
    visibility: hidden;
  }
  .rectangle {
    border: solid 5px;
  }
  .logo2 {
    height: 10px;
    width: 200px;
  }
  .quickSummary {
    padding-top: 0;
  }
  .theAwardTitle {
    font-size: 2.5rem;
  }
  .thePriceToPayTitle {
    font-size: 2.5rem;
  }
}
/* ----------- iPhone X ----------- */
/* Portrait and Landscape */
@media only screen and (min-device-width: 180px) and (max-device-width: 812px) and (-webkit-min-device-pixel-ratio: 3) {
  .dragonHeadLeft {
    visibility: hidden;
  }
  .dragonHeadRight {
    visibility: hidden;
  }
  .rectangle {
    border: solid 5px;
  }
  .logo2 {
    height: 10px;
    width: 200px;
  }
  .theAward {
    padding-top: 70px;
  }
  .quickSummary {
    padding-top: 0;
  }
  .theAwardTitle {
    font-size: 2.5rem;
  }
  .thePriceToPayTitle {
    font-size: 2.5rem;
  }
  .logo2right {
    position: unset;
  }
}
</style>