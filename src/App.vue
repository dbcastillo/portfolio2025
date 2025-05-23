<template>
  <v-sheet>
    <v-container class="d-flex flex-column mb-6">
      <v-sheet class="pa-6 my-10 elevation-2 rounded w-100 text-center"
               style="background-color: #f7fcfe; min-height: 200px">
        <h1 class="text-h1 pb-4">Derick Castillo</h1>
        <h2 class="text-h4">Software Engineer</h2>
      </v-sheet>
      <!-- Option 1: Using align-stretch on v-row (simplest solution) -->
      <v-row align="stretch">
        <v-col class="d-flex flex-column ga-8" cols="12" md="6">
          <v-sheet class="pa-4 elevation-2 rounded" style="background-color: #f7fcfe">
            <div class="mb-2" style="display: inline-block;">
              <h1 class="text-h5 font-weight-bold">MY CONTACT</h1>
              <div
                  style="height: 6px; width: 100%; background-color: black; border-radius: 3px; margin: 8px 0;"
              ></div>
            </div>
            <p class="mb-4 d-flex align-center">
              <v-icon class="me-2" icon="mdi-email"/>
              derick.ben.castillo@gmail.com
            </p>
            <p class="mb-4 d-flex align-center">
              <v-icon class="me-2" icon="mdi-phone"/>
              312-256-6554
            </p>
            <p class="mb-4 d-flex align-center">
              <v-icon class="me-2" icon="mdi-map-marker"/>
              Nashville, Tennessee
            </p>
            <p class="mb-4 d-flex align-center">
              <v-icon class="me-2" icon="mdi-web"/>
              <a href="https://derick-castillo.netlify.app" rel="noopener noreferrer" target="_blank">
                derick-castillo.netlify.app
              </a>
            </p>
          </v-sheet>

          <v-sheet class="pa-4 elevation-2 rounded" style="background-color: #f7fcfe">
            <div class="mb-2" style="display: inline-block;">
              <h1 class="text-h5 font-weight-bold">SKILLS</h1>
              <div
                  style="height: 6px; width: 100%; background-color: black; border-radius: 3px; margin: 8px 0;"
              ></div>
            </div>
            <ul class="pl-4">
              <li>JavaScript</li>
              <li>React.js</li>
              <li>Java</li>
              <li>BFF Architecture</li>
              <li>Ruby/Rails</li>
              <li>MVC pattern</li>
              <li>HTML/CSS</li>
              <li>SQL</li>
              <li>Rspec/Jest/Unit Testing</li>
              <li>Git</li>
              <li>Jira</li>
              <li>Postman</li>
              <li>Agile Methodology</li>
              <li>VS Code / IntelliJ</li>
            </ul>
          </v-sheet>
          <v-sheet class="pa-4 elevation-2 rounded" style="background-color: #f7fcfe">
            <div class="mb-2" style="display: inline-block;">
              <h1 class="text-h5 font-weight-bold">EDUCATION</h1>
              <div
                style="height: 6px; width: 100%; background-color: black; border-radius: 3px; margin: 8px 0;"
              ></div>
            </div>
            <div class="mb-4">
              <p class="text-subtitle-1 font-weight-bold">Flatiron School</p>
              <p class="text-body-2">Software Engineering</p>
              <p>2018</p>
            </div>
            <div class="mb-4">
              <p class="text-subtitle-1 font-weight-bold">Triton College</p>
              <p class="text-body-2">Nuclear Medicine</p>
              <p>2011</p>
            </div>
          </v-sheet>
          <!-- Add flex-grow-1 to make this sheet fill remaining space -->
          <v-sheet class="pa-4 elevation-2 rounded flex-grow-1" style="background-color: #f7fcfe">
            <div class="mb-2" style="display: inline-block;">
              <h1 class="text-h5 font-weight-bold">AFFILIATIONS</h1>
              <div
                style="height: 6px; width: 100%; background-color: black; border-radius: 3px; margin: 8px 0;"
              ></div>
            </div>
            <div class="mb-4">
              <p class="text-subtitle-1 font-weight-bold">Moove DJ Group</p>
              <p class="text-body-2">Professional Wedding Emcee and DJ</p>
              <p class="text-body-2">Occasional Private Events</p>
            </div>
            <div class="mb-4">
              <p class="text-subtitle-1 font-weight-bold">Church of the City Nashville Volunteer</p>
              <p class="text-body-2">Serve at Room-at-the-Inn Homeless Shelter</p>
            </div>
          </v-sheet>
        </v-col>

        <v-col class="d-flex flex-column ga-8" cols="12" md="6">
          <v-sheet class="pa-4 elevation-2 rounded" style="background-color: #f7fcfe">
            <div class="mb-2" style="display: inline-block;">
              <h1 class="text-h5 font-weight-bold">ABOUT ME</h1>
              <div
                  style="height: 6px; width: 100%; background-color: black; border-radius: 3px; margin: 8px 0;"
              ></div>
            </div>
            <p class="mb-10">
              I'm a passionate Software Engineer with 5+ years of relevant experience. My roles in various industries
              have developed my leadership ability and strong communication skills. My ability to quickly adapt in the
              midst of change, collaborate well as a team player, and learn new concepts quickly, will make me an
              asset across all phases of product development.
            </p>
          </v-sheet>

          <!-- Add flex-grow-1 to make this sheet fill remaining space -->
          <v-sheet class="pa-4 elevation-2 rounded flex-grow-1" style="background-color: #f7fcfe">
            <div class="mb-2" style="display: inline-block;">
              <h1 class="text-h5 font-weight-bold">PROFESSIONAL EXPERIENCE</h1>
              <div
                  style="height: 6px; width: 100%; background-color: black; border-radius: 3px; margin: 8px 0;"
              ></div>
            </div>
            <div class="mb-6">
              <p class="mb-2 text-subtitle-1 font-weight-bold">
                <span>Ramsey Solutions</span>
                <span class="mx-2">-</span>
                <span>Software Engineer 2</span>
                <span class="mx-2">-</span>
                <span>2023–Current</span>
              </p>
              <ul class="pl-8">
                <li class="mb-2">Support a team of real estate coaches by developing UI enhancements on a dashboard
                </li>
                <li class="mb-2">Contribute to the maintenance and enhancement of a company mobile app, working with
                  React Native
                  and Java
                </li>
                <li class="mb-2">Collaborate with multiple teams to build a web app from scratch for a new product
                  offering,
                  leveraging Vue.js and Java on the frontend and backend
                </li>
              </ul>
            </div>
            <div class="mb-6">
              <p class="mb-2 text-subtitle-1 font-weight-bold">
                <span>7-Eleven</span>
                <span class="mx-2">-</span>
                <span>Fullstack Software Engineer</span>
                <span class="mx-2">-</span>
                <span>2022-2023</span>
              </p>
              <ul class="pl-8">
                <li class="mb-2">Maintain proprietary Delivery Audit App, adding features using React
                </li>
                <li class="mb-2">Add unit tests in React.js and Jest to improve code coverage
                </li>
                <li class="mb-2">Collaborate with agile team to refactor backend/frontend logic
                </li>
                <li class="mb-2">Assist with product management, reporting, business updates</li>
              </ul>
            </div>
            <div class="mb-6">
              <p class="mb-2 text-subtitle-1 font-weight-bold">
                <span>Cognizant</span>
                <span class="mx-2">-</span>
                <span>Fullstack Software Engineer</span>
                <span class="mx-2">-</span>
                <span>2021</span>
              </p>
              <ul class="pl-8">
                <li class="mb-2">Design and architecture of frontend medical dashboard utilizing Unqork, React.js, Git,
                  HTML & CSS
                </li>
                <li class="mb-2">Add unit testing suite in React.js with Jest to increase test coverage</li>
                <li class="mb-2">Collaborate with an agile team to create a functional backend API for contractors to
                  bill for
                  services
                </li>
                <li class="mb-2">Integration of full CRUD functionality, deploys via Heroku, Docker</li>
              </ul>
            </div>
            <div class="mb-6">
              <p class="mb-2 text-subtitle-1 font-weight-bold">
                <span>Flatiron School</span>
                <span class="mx-2">-</span>
                <span>Software Engineering Instructor</span>
                <span class="mx-2">-</span>
                <span>2019-2021</span>
              </p>
              <ul class="pl-8">
                <li class="mb-2">Successful leadership of 6 cohorts, 100+ students, adhering to company outcomes
                  generating positive
                  reviews
                </li>
                <li class="mb-2">Web app creation in Rails/React.js to demonstrate work-flow standards
                </li>
                <li class="mb-2">Hold weekly office hours with a focus on core Ruby/JavaScript concepts
                </li>
                <li class="mb-2">Lectures on Rails/JavaScript/React.js, mentorship via pair programming, code
                  challenges, mock
                  interviews
                </li>
              </ul>
            </div>
          </v-sheet>
        </v-col>
      </v-row>
    </v-container>
  </v-sheet>
</template>