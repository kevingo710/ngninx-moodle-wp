## INFRAESTRUCTURE NGINX-LETSENCRYPT + WORDPRESS*2 + MOODLE

Clone this project
  1. Clone repo
  2. Change domains in docker-compose
  2. `docker-compose up -d` ./
  3. `docker-compose up -d` /anyService
  4. Moodle after install error IP-> check nginx_container IP & exec in moodleDB_container `docker exec -it moodleDB_container mysql -uroot -p`  -> `use moodledb`;
  --> `UPDATE mdl_user set lastip='172.docker.nginx.IP' where username='admin';`
  5. WordPress Plugin e-mail -> [WP Mail SMTP by WPForms](https://es.wordpress.org/plugins/wp-mail-smtp/)
  6. WordPress Plugin contact-form -> [Contact Form 7](https://es.wordpress.org/plugins/contact-form-7/) 

### _Resources_:
* DigitalOcean 🛫
* Docker 🐳



## Expressions of gratitude 🎁

* Share this project 📢
* Invite me a coffee ☕  




---


<p>
    <a href="https://twitter.com/intent/follow?screen_name=kevingrac7">
    <img src="https://img.shields.io/twitter/follow/kevingrac7?style=social"
    alt="follow on Twitter">
    </a>
<p>
