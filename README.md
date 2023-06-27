# School Project to practice React Routers

## About this project
* Pet adoption website that allows users to view all the animals of a particular species and view the profiles of specific animals.
* Homepage shows all the adoptable pets
* There is also a pet detail page, that shows more info about a pet

## Objective: Using Client side routing, do the following:
### Home Page
* The HomePage component responds to the browser’s current URL by displaying only pets of the species the user wishes to view.

### Detail Page
* The PetDetailsPage page displays when the browser’s current URL includes a specific pet’s id.
* The PetDetailsPage displays data for the correct pet based on the id in the URL parameters’ values.

### Search Feature
* When the user searches for a pet in the search bar, they are redirected to the SearchPage, which uses the query parameter called name to filter pets by name.

### 404 page
* When a user clicks a pet whose details are not available, they are redirected to a PetNotFoundPage.
* From the PetNotFound page, users can click “Go Home” button that will take them to the root path page.
