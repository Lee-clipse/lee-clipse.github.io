---
layout: single
comments: false
permalink: /portfolio/
title: "Lee Jinjae"
classes: wide
---

> Backend Engineer

<h1>Project<span class="period-mark">.</span></h1>

<h2>01) 청건부산 2nd Website<span class="period-mark">.</span></h2>

> Mobile-exclusive website for the 16th Together Festival and the Cheonggeon Busan 2nd event.

- Sponsored by [Busan Metropolitan City](https://www.busan.go.kr/index), organized by the [(사)십대의벗청소년교육센터](http://m.octm1318.com/)

- 2024.07 ~ 2024.09

<h3>Description<span class="period-mark">.</span></h3>

As the lead developer for this project, which I managed for the second consecutive year, <br/>I was responsible for a service providing event information and activity visualization to 4,200 Daily Active Users (DAU) in Busan.
<br/> I collaborated with an illustrator and the event committee to develop the website. <br/>
I implemented APIs suited to the event planning and interactive content, <br/> while also handling front-end and DevOps tasks within the given environment and resources.

<h3>What did I do<span class="period-mark">.</span></h3>

- Developed an API server running 32 APIs.
- Implemented a booth activity visualization game called `Zero Game`.
- Developed a cookie-based user and staff registration and authentication system.
- Built a custom server logging system.
- Designed and implemented all necessary front-end, UI, and ERD.
- Communicated with external stakeholders regarding project status, requirements, and planning.

<h3>Hyperlink<span class="period-mark">.</span></h3>

- Live site (mobile only): [https://busan-tf.n-e.kr/](https://busan-tf.n-e.kr/)
- Github: [https://github.com/Lee-clipse/tf-16th-website](https://github.com/Lee-clipse/tf-16th-website)

<h2>02) DID and ZKP-Based Identity Verification System<span class="period-mark">.</span></h2>

> A Web3 identity verification system implemented using Decentralized Identifiers (DID) and Zero-Knowledge Proofs (ZKP).

- Graduation Project, Pusan National University, 2023

- 2024.03 ~ 2024.06

<h3>Description<span class="period-mark">.</span></h3>

This project aimed to move away from traditional centralized DB by implementing a DID protocol that aligns with Web3 standards.
<br/> Utilized the Near Smart Contract platform to implement the DID protocol and Snark.js library to build the ZKP circuit.<br/>
The system verifies the identity of Pusan National University students through a custom-built Chrome Extension Wallet.
<br/> Both the FE and BE communicate with a blockchain server, ensuring that no personal data is stored in a centralized DB while performing student identity verification.

<h3>What did I do<span class="period-mark">.</span></h3>

- Designed the infrastructure and managed the DB.
- Developed Holder, Issuer, Verifier, and Server API servers.
- Implemented server-blockchain network communication using the Snark.js library.

<h3>Hyperlink<span class="period-mark">.</span></h3>

- Github: [https://github.com/2024-Circular-Reference/identity-verify-WAS](https://github.com/2024-Circular-Reference/identity-verify-WAS)

<h2>03) Ontact Korea Service<span class="period-mark">.</span></h2>

> A parcel forwarding service for international customers shipping Korean goods abroad.

- Outsourced project for [(주)에버스톤](http://www.evst.co.kr/)
- 4-month internship at Pusan National University, practical experience program

- 2024.03 ~ 2024.06

<h3>Description<span class="period-mark">.</span></h3>

This service, used by around 4,600 users across 195 countries, launched officially in June 2024 after a 4-month development period. <br/> Users primarily use the platform for purchase and shipping forwarding services.
<br/> The admin page allows handling of requests by providing quotes and visualizing internal warehouse management. <br/> The service supports international payments via PayPal for four external carriers (FedEx, UPS, etc.).

<h3>What did I do<span class="period-mark">.</span></h3>

- Developed coupon service, review, and announcement features using `무신사` and `오늘의 집` as references.
- Utilized open APIs from FedEx, UPS, and others to calculate international shipping rates.
- Implemented payment, refund, and partial refund transactions using the PayPal API.
- Built a database backup system scheduled to run at specific times.
- Created middleware for image compression and to unify various time zones into UTC.
- Led the initial deployment of the service using docker-compose and implemented SSL certificate renewal.
- Refactored the existing website to be optimized for mobile users.
- Managed UI components using Figma.
- Introduced Flow collaboration tool for managing development timelines and maintenance.
- Communicated with foreign customer service staff within the outsourcing company.

<h3>Hyperlink<span class="period-mark">.</span></h3>

- Live Service: [https://ontactkorea.net/](https://ontactkorea.net/)

<h2>04) 청건부산 1st Website<span class="period-mark">.</span></h2>

> Mobile-exclusive website for the 15th Together Festival and Cheonggeon Busan 1st event.

- Project sponsored by [Busan Metropolitan City](https://www.busan.go.kr/index)
- Organized by the [(사)십대의벗청소년교육센터](http://m.octm1318.com/)

- 2023.08 ~ 2023.09

<h3>Description<span class="period-mark">.</span></h3>

This service provided event information for a Busan event with 1,700 Daily Active Users (DAU). <br/> I collaborated with event planners and the committee to develop the website. <br/>
I developed two API servers: one for content and one for a game, and set up the necessary front-end and cloud infrastructure.

> As the sole developer, I implemented the required front-end and DevOps infrastructure by referencing and learning from minimal resources as needed.

<h3>What did I do<span class="period-mark">.</span></h3>

- Developed an API server running 14 APIs.
- Created a team-based board game service using dice.
- Implemented a QR code-based system for user team creation and participation.
- Built a staff authentication system using LocalStorage to reduce API traffic.
- Developed a custom server logging system.
- Implemented zero-downtime deployment using pm2 with multi-process architecture.

<h3>Hyperlink<span class="period-mark">.</span></h3>

- Live Site (mobile only): [https://busan-tf.n-e.kr/](https://busan-tf.n-e.kr/) (service ended)
- Github: [https://github.com/Lee-clipse/tf-15th-website](https://github.com/Lee-clipse/tf-15th-website)

<h2>05) Fitory<span class="period-mark">.</span></h2>

> A PWA service that tracks workout records with social features, displaying your three main lifts (bench press, squat, deadlift) ranked and tiered among users of similar weight classes.

- Team project for Naver Boostcamp Web & Mobile 7th cohort

- 2022.11 ~ 2022.12

<h3>Description<span class="period-mark">.</span></h3>

Fitory is a workout tracking and social networking service designed to motivate users by visualizing their exercise data. <br> The project was developed and deployed by a team of 2 FE and 2 BE developers. <br> As this was my first team project, I gained experience in establishing a development culture, including Git conventions, <br>Figma-based planning, and writing API specifications.

<h3>What did I do<span class="period-mark">.</span></h3>

- Developed an API server running 28 APIs.
- Built an SNS notification system using Server-Sent Events (SSE).
- Optimized performance of statistical APIs for workout data using Multi-Column Indexing.
- Developed a file compression and storage pipe for user-uploaded photos using Nest.js.
- Conducted API performance testing and refactored CPU-intensive code using k6 and Clinic.js.

<h3>Hyperlink<span class="period-mark">.</span></h3>

- Live site (mobile only): [https://fitory.ga/](https://fitory.ga/) (service ended)
- Github: [https://github.com/boostcampwm-2022/Web04-Fitory](https://github.com/boostcampwm-2022/Web04-Fitory)

<h1>Skill<span class="period-mark">.</span></h1>

<h3>Communication<span class="period-mark">.</span></h3>

- I believe it's important not to make assumptions or passively react to requirements or specific functionalities.
- I strive to confirm the intent behind any suggestions, as I am cautious about the potential side effects of giving up communication due to fear of my opinions not being implemented.
- I believe that clear code and transparent communication come from a well-rested mind.

<h3>Node.js<span class="period-mark">.</span></h3>

- Proficient in using Node.js to implement efficient asynchronous processing and event-driven architecture.
- Capable of designing and building RESTful APIs using key frameworks like Express.js.
- Experienced in developing interactive web applications by implementing real-time data communication using WebSocket.

<h3>Nest.js<span class="period-mark">.</span></h3>

- Able to write API test code using Testing Library.
- Understand the Nest.js lifecycle and MVC architecture, allowing for the implementation of Guards, Interceptors, and Pipes based on use cases.
- Skilled in proper dependency injection to reduce coupling and perform module-level testing.
- Experienced in safely interacting with databases using DTO and ORM.

<h3>Database<span class="period-mark">.</span></h3>

- Capable of selecting NoSQL or RDB based on service requirements and read/write performance needs.
- Able to design ERDs and determine the need for table normalization through scenario testing.
- Skilled in measuring query cost through various scan methods and applying single or multi-column indexing.
- Experienced in implementing pre- and post-processing of data requests using MySQL Triggers.

<h3>DevOps<span class="period-mark">.</span></h3>

- Proficient in setting up web infrastructure using Nginx, ACG, and Cloud DB in a cloud environment.
- Experienced in implementing zero-downtime deployments in a multi-process environment using tools like pm2.

<h1>Contact<span class="period-mark">.</span></h1>

- Email: jamjam1208@naver.com
- Blog: [https://lee-clipse.github.io/](https://lee-clipse.github.io/)
- GitHub: [https://github.com/lee-clipse](https://github.com/lee-clipse)
