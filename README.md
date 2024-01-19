# Nomad Nest
<!-- <div id="description" align="center">
![Profile](favicon.png)
</div> -->
| URI | REST Route | HTTP Method | CRUD Action | EJS View |
|-----|------------|-------------|-------------|----------|
| / | | GET | read | home.ejs |
| /destinations | index | GET | read | destination-index.ejs |
| /destinations/:id | show | GET | read | destination-details.ejs |
| /destinations/new | new | GET | | new-form.ejs |
| /destinations | create | POST | create | |
| /destinations/:id/edit | edit | GET | read | edit-form.ejs |
| /destinations/:id | update | PUT | update | |
| /destinations/:id | delete | DELETE | delete | |
| /reviews/ | index | GET | read | review-index.ejs |
| /reviews/:id | show | GET | read | review-details.ejs | 
| /reviews/new/:destinationId | new | GET | read | new-form.ejs |
| /reviews/create/:destinationId | create | POST | create | |
| /reviews/:id | destroy | DELETE | delete | |
| /seed | | GET | delete & create | |

## :art: Screenshots

<details open>
<summary>Wireframe-Home</summary>

![Home](public/assets/screenshots/home.png)
</details>

<details open>
<summary>Wireframe-Details</summary>

![Details](public/assets/screenshots/details.png)
</details>

<details open>
<summary>Home</summary>

![Home](home.png)
</details>

<details open>
<summary>Index</summary>

![Destination-index](projects-1.png)
</details>

<details open>
<summary>Show</summary>

![Destination-show](game.png)
</details>

<details open>
<summary>New & Create</summary>

![New Destination](about-screenshot.png)
</details>

<details open>
<summary>Edit & Update</summary>

![Edit Destination](contact.png)
</details>

<details open>
<summary>Second Schema - Reviews</summary>

![Create a Review](contact.png)
</details>

## :robot: Technologies Used

https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=whiten https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white  https://img.shields.io/badge/Express.js-404D59?style=for-the-badge https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white ![CSS3](https://img.shields.io/badge/-CSS-05122A?style=flat&logo=css3) ![JavaScript](https://img.shields.io/badge/-JavaScript-05122A?style=flat&logo=javascript)

## :link: Links

<details open>
<summary>Deployed Link</summary>
<a href="https://nomad-nest-3b3484e95287.herokuapp.com/">Nomad Nest</a>
</details>

## :rocket: Walkthrough

Welcome to Nomad Nest: a site created to assist digital nomads. Pick a location and we'll help you getting settled in your new home away from home. We'll provide and book recommended stays, assist with visa requirements, offer information about transportation, co-working spaces and more. Explore our list of destinations and find reviews posted by digital nomads. Are you ready to buckle up?

<!-- ## :pencil: User Stories

- As someone just met at a networking event, I want to quickly see the developer's skills, so that I can recommend the person to my company or someone who I know. 
- As a non-technical HR manager, I want to quickly see the skills and experience of a candidate, so that I can evaluate whether the candidate meets the requirements for an open position at my company.
- As a mid-level engineer, I want to view a junior developer's project and read their code, so that I can evaluate their coding skills. -->


## :triangular_flag_on_post: Unsolved Problems & Hurdles

- Improve the UI on smaller screens


## :dart: Next Steps

- [ ] Improve the UI
- [ ] Add features and complete the app