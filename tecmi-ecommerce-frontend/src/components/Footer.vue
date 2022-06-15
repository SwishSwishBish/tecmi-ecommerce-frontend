<template>
  <footer className="nb-footer ">
    <div className="container">
      <div className="row">
        <div className="col-sm-12">
          <div className="about">
            <div className="social-media">
              <ul className="social-list">
                <li><a href="https://github.com/SwishSwishBish" title="" target="_blank"><img
                      src="https://img.icons8.com/ios/35/undefined/github--v1.png" /></a></li>
                <li><a href="https://www.linkedin.com/in/sena-atak%C3%B6%C5%9Fker-3a79b0235/" title=""
                    target="_blank"><img src="https://img.icons8.com/ios/35/undefined/linkedin-circled--v1.png" /></a>
                </li>
                <li><a href="https://twitter.com/SenaAtakosker" title="" target="_blank"><img
                      src="https://img.icons8.com/ios/35/undefined/twitter-circled--v1.png" /></a></li>
                <li><a href="https://www.facebook.com/theyoungturk/" title="" target="_blank"><img
                      src="https://img.icons8.com/ios/35/undefined/facebook-circled--v1.png" /></a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>

    <section className="copyright">
      <div className="container">
        <div className="row">
          <div className="col-sm-12 text-center">
            <p>Copyright © 2022. Sena Atakosker</p>
          </div>
        </div>
      </div>
    </section>
  </footer>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style>
.social-list {
  display: flex;
  list-style: none;
  justify-content: center;
  padding: 0;
}

.social-list li {
  padding: 7px;
  color: #fca552;
  font-size: 19px;
}

footer.nb-footer {
  margin-top: 200px;
  background: #32c7f846;
  border-top: 4px solid #0c7fbb;
}

footer.nb-footer .about {
  margin: 0 auto;
  margin-top: 0px;
  max-width: 1170px;
  text-align: center;
}

footer.nb-footer .about p {
  font-size: 13px;
  color: #999;
  margin-top: 0px;
}

footer.nb-footer .about .social-media {
  margin-top: 0px;
}

footer.nb-footer .about .social-media ul li a {
  display: inline-block;
  width: 35px;
  height: 35px;
  border-radius: 100%;
  font-size: 15px;
  color: #fca552;
}

footer.nb-footer .about .social-media ul li a:hover {
  background: #32c5f8;
  color: #fff;
  border-color: #2cd3dc;
}

footer.nb-footer .footer-info-single {
  margin-top: 0px;
}

footer.nb-footer .footer-info-single .title {
  color: #aaa;
  text-transform: uppercase;
  font-size: 16px;
  border-left: 4px solid #fca552;
  padding-left: 5px;
}

footer.nb-footer .footer-info-single ul li a {
  display: block;
  color: #aaa;
  padding: 2px 0;
}

footer.nb-footer .footer-info-single ul li a:hover {
  color: #fca552;
}

footer.nb-footer .footer-info-single p {
  font-size: 13px;
  line-height: 20px;
  color: #aaa;
}

footer.nb-footer .copyright {
  margin-top: 0px;
  background: #0c7fbb;
  padding: 0px 0;
  color: rgb(255, 255, 255);
}

footer.nb-footer .copyright p {
  margin: 0;
  padding: 0;
}

footer {
  font-family: 'Roboto', sans-serif;
}
</style>
