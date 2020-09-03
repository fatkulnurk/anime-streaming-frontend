<script>
    import {Router} from "@sveltech/routify";
    import {routes} from "../.routify/routes";
</script>

<style  global>
  @import "../static/global.css";
  #routify-app > section.section > div > div > div > div > a {
      color: #282222 !important;
      text-decoration: underline !important;
  }
</style>

<nav class="navbar container" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
<!--        <a class="navbar-item" href="https://bulma.io">-->
<!--            <img src="https://bulma.io/images/bulma-logo.png" width="112" height="28">-->
<!--        </a>-->
        <a href="/" class="navbar-item has-text-weight-bold">AnimeFlix</a>

        <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
        </a>
    </div>

    <div class="navbar-menu">
        <div class="navbar-start">
            <a href="/" class="navbar-item">
                Home
            </a>

            <a href="/" class="navbar-item">
                Genre
            </a>

            <a href="/" class="navbar-item">
                List Anime
            </a>

        </div>

        <div class="navbar-end">
            <div class="navbar-item">
                <div class="buttons">
                    <a href="/" class="button is-light">
                        Log in
                    </a>
                </div>
            </div>
        </div>
    </div>
</nav>

<!--<Hero title="mbuh opo" description="lorem imsum dotsum siramet"/>-->

<Router {routes} />

<footer class="footer">
    <div class="container has-text-centered">
        &copy; 2020 AnimeFlix - Nonton dan Download Anime Online Terlengkap Sub Indonesia <br>
        Disclaimer: This site does not store any files on its server.<br>
        All contents (information, poster, vidio, and etc) are provided by non-affiliated third parties <br>
        <hr>
        website ini juga dapat di akses menggunakan jaringan tersembunyi dengan alamat http://animeflixdahdeiurrwr.onion
    </div>
</footer>