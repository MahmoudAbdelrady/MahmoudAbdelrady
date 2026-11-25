<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img alt="Mahmoud Abdelrady, software engineer in Cairo" src="assets/header-dark.svg" width="100%">
</picture>

Hi, I'm Mahmoud. I'm a full-stack software engineer in Cairo, currently at **Banque Misr**. Before that I spent two years at **Maids.cc** building the Sales and CRM modules of a large microservices ERP with Java, Spring Boot and Kafka.

Most of my free time goes into building something of my own, taking it from a rough idea all the way to a live deployment on my own server at [mdevs.cloud](https://mdevs.cloud). I care about understanding why things work, not just getting them to work, and I'm always chasing the next thing that pushes me out of my comfort zone.

## Projects

<table>
<tr>
<td width="50%" valign="top">

#### [Cinefy](https://github.com/MahmoudAbdelrady/Cinefy)

Open-source cinema management and booking platform, with a customer site, an admin panel and a box-office POS.

- Seat booking that can't double-sell, using PostgreSQL partial unique indexes and optimistic concurrency, load-tested with JMeter
- Pluggable payment gateways: admins register Paymob, Stripe and others, then switch the active one from the UI without a deploy
- Saved cards, idempotency keys, seat holds that expire, QR ticket check-in, Google and Microsoft sign-in

`Java` `Spring Boot` `Angular` `PostgreSQL`

**[Live demo →](https://cinefy.mdevs.cloud)**

</td>
<td width="50%" valign="top">

#### Clipzy &nbsp;<sub>in progress</sub>

Upload a video, get a link that works for the length of the video plus an hour, then it's gone.

- Gateway, Identity, Uploader and Transcoder services, each with its own database
- Clients upload straight to Cloudflare R2 through pre-signed URLs
- RabbitMQ hands uploads to the transcoder, which runs ffmpeg and serves HLS in several qualities
- Built to be my Kubernetes playground once it's done

`Kotlin` `Spring Boot` `React` `PostgreSQL` `RabbitMQ` `ffmpeg`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Trackera](https://github.com/MahmoudAbdelrady/Trackera)

Jira worklog tracker and calculator. Pulls your logged hours from Jira and does the math so you don't have to. Background jobs run through RabbitMQ.

`Java` `Spring Boot` `React` `MySQL` `RabbitMQ`

**[Live demo →](https://trackera.mdevs.cloud)**

</td>
<td width="50%" valign="top">

#### [Shortenly](https://github.com/MahmoudAbdelrady/Shortenly)

A URL shortener.

`Spring Boot` `Angular` `PostgreSQL`

</td>
</tr>
</table>

## Tools I reach for

<p>
  <img src="https://skillicons.dev/icons?i=java,kotlin,spring,gradle,ts,angular,react&theme=dark" alt="Java, Kotlin, Spring, Gradle, TypeScript, Angular, React"><br>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,redis,kafka,rabbitmq,docker,kubernetes,nginx,cloudflare,gcp,linux&theme=dark" alt="PostgreSQL, MySQL, Redis, Kafka, RabbitMQ, Docker, Kubernetes, Nginx, Cloudflare, GCP, Linux">
</p>

## Say hi

[LinkedIn](https://www.linkedin.com/in/mahmoudabdelrady10) · [mdevs.cloud](https://mdevs.cloud)
