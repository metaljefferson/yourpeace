<template>
  <footer>
    <div class="footer-principal">
      <div>
        <div class="footer-logo">
          <img src="../assets/img/flor.svg" alt="" />
          <div>
            <p class="footer-private">Private Oracle</p>
            <p class="footer-url"><a href="#">www.privateoracle.com</a></p>
          </div>
        </div>
        <div class="footer-copy">
          <p>Copyright © 2021 · Private Oracle ·</p>
        </div>
        <div class="footer-contact">
          <p>Privacy Policy</p>
          <p>Terms and Conditions</p>
          <p>Contact Us</p>
        </div>
      </div>

      <div class="footer-social">
        <p class="footer-keep">Keep In Touch</p>
        <div class="footer-logos">
          <img src="../assets/img/facebook.svg" alt="facebook" />
          <img src="../assets/img/gatinho.svg" alt="github" />
          <img src="../assets/img/Insta.svg" alt="instagram" />
          <img src="../assets/img/pinterest.svg" alt="pinterest" />
          <img src="../assets/img/twitter.svg" alt="twitter" />
          <img src="../assets/img/youtube.svg" alt="youtube" />
        </div>
        <p class="footer-country">
          <span
            >You must be of legal adult age as per your country’s requirements
            to use this service.</span
          ><span>
            Please note this service is for entertainment purposes only, you are
            responsible for all your life decision.</span
          >
        </p>
      </div>
    </div>
  </footer>
</template>
<style lang="scss">
.footer-principal {
  background: #09b3b0;
  border-radius: 0px;
  display: flex;
  padding: 60px;
  align-items: center;
  margin-top: 3.75rem;
}
.footer-logo {
  display: flex;
  align-items: center;
  gap: 1rem;
}
.footer-keep {
  font-family: Aleo;
  font-style: normal;
  font-weight: normal;
  font-size: 17px;
  line-height: 22px;
  color: #ffffff;
}
.footer-country {
  span {
    display: block;
    font-family: Montserrat;
    font-style: normal;
    font-weight: normal;
    font-size: 13px;
    line-height: 24px;
    color: #ffffff;
    text-align: left;
  }
}
.footer-logos {
  display: flex;
  gap: 1rem;
}
.footer-private {
  font-family: Aleo;
  font-style: normal;
  font-weight: normal;
  font-size: 22px;
  line-height: 26px;
  color: white;
}
.footer-url {
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 13px;
  line-height: 24px;

  a {
    text-decoration: none;
    color: white;
  }
}
.footer-contact {
  display: flex;
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 12px;
  letter-spacing: 1px;
  text-transform: uppercase;
  color: #ffffff;
  p:not(:last-child) {
    border-right: 1px solid #fff;
  }
  p {
    padding-right: 15px;
    padding-left: 15px;
  }
  p:first-child {
    padding-left: 0;
  }
}
.footer-social {
  display: flex;
  gap: 1rem;
  flex-direction: column;
  width: 14.5rem;
  text-align: left;
}
.footer-copy {
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 13px;
  line-height: 13px;
  color: white;
  display: flex;
}
</style>
