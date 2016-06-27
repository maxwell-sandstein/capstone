# Facebook

[Heroku link][heroku]

[heroku]: http://www.herokuapp.com

## Minimum Viable Product

Facebook is a web application inspired by Mark Zuckerberg's original Facebook that will be build using Ruby on Rails and React.js.  By the end of Week 9, this app will, at a minimum, satisfy the following criteria:

- [ ] Hosting on Heroku
- [ ] New account creation, login, and guest/demo login
- [ ] A production README, replacing this README 
- [ ] Smooth, bug free navigation
- [ ] Search bar for friends and events
- [ ] Privacy Settings
- [ ] News Feed
- [ ] Notifications
- [ ] Private Messages
-  [ ] Profile Page
  - [ ] Cover Photo
  - [ ] Timeline
  - [ ] Friends List
  - [ ] About
- [ ] Friend Requests
- [ ] Events
- [ ] Likes
- [ ] Adequate CSS styling

- [ ] Bonus Features
  - [ ] People You May Know
  - [ ] News Feed Algorithm 
 

## Design Docs
* [View Wireframes][views]
* [React Components][components]
* [Flux Cycles][flux-cycles]
* [API endpoints][api-endpoints]
* [DB schema][schema]

[views]: docs/views.md
[components]: docs/components.md
[flux-cycles]: docs/flux-cycles.md
[api-endpoints]: docs/api-endpoints.md
[schema]: docs/schema.md

## Implementation Timeline (Styling to be done with features as implemented)

### Phase 1: Auth (1 day)

**Objective:** Functioning rails project with Authentication

- [ ] create new project
- [ ] create `User` model
- [ ] authentication
- [ ] user signup/signin pages
- [ ] blank landing page after signin

### Phase 2: Nav Bar (0.5 days)

**Objective:** Create Navbar

- [ ] create Navbar to be rendered when session is active

### Phase 3: Profile (1.5 days)

**Objective:** Profile can be seen and created

- [ ] Profile Model
- [ ] Seed
- [ ] Profiles Controller
- [ ] Jbuilder Views
- [ ] Weback and Flux scaffold
- [ ] APIUtil
- [ ] Flux Loop
- [ ] React Router
- [ ] Components
  - [ ] Cover Photo
  - [ ] Profile Picture
  - [ ] Name Link
  - [ ] Request
  - [ ] Intro Index



### Phase 4: Update (0.5 days)

**Objective:** Profile can be updated

- [ ] Everything from phase 3 on the update side
- [ ] Components
  - [ ] Update Form
  - [ ] Update Index 
  - [ ] Update Index Item

### Phase 5: Comments (1 day)

**Objective:** Comments CRUD

- [ ] Comment Model
- [ ] Comment Controller
- [ ] jBuilder views
- [ ] APIutil
- [ ] test API in console
- [ ] flux loop
- [ ] React Router
- [ ] components
  - [ ] Comments Index with items and a form


### Phase 6: Search Bar (1 day)

**Objective:** Search bar shows links to users

- [ ] Ajax to return users
- [ ] render based on returned users
- [ ] Inject into navbar
- [ ] components
  - [ ] search bar, results Index, results index item
 


### Phase 7: Request (1 day)

**objective:** Requests CRUD

- [ ] Requests Model
- [ ] Seed
- [ ] jBuilder views
- [ ] flux loop
- [ ] Components
  - [ ] Request Button
  - [ ] Request Index with request item nested

### Phase 8: Notifications (0.5 days)

**objective:** Notifications CRUD

- [ ] The aforementioned CRUD stuff but for notifications


### Phase 9: Cleanup (0.5 days)

- [ ] CSS Refactoring

### Bonus Features (TBD)

