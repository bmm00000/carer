# Summary

"Carer" is a responsive web app where freelance caregivers can advertise their services, and their clients can review them.

See live:
Watch demo:

Non-authenticated users are authorised to see the whole list of caregivers, their location in a cluster map, their individual profiles, their individual location in an individual map, and the reviews submitted by their clients.

Authenticated users are authorised to the same as non-authenticated ones, plus they can also message caregivers, and submit reviews of their services. Authenticated users can delete reviews only if they created them.

Authenticated users who identify as caregivers can create their profiles advertising their services, adding a description, price, location (that will appear in the maps), and add one or more pictures that will be displayed in a carousel.

Authenticated users who are profile owners (caregivers) can edit or delete only their own profile, as well as add or delete one or more of their own pictures. However, they cannot submit reviews to their own profile.

- Architectural style: REST
- Design pattern: MVC

# Main technologies

HTML, CSS, JavaScript, Node.js, Express, MongoDB

# Getting started

Make sure you have installed Node.js in your system.

## Clone this repository

`git clone https://github.com/bmm00000/carer.git`

## Install dependencies

`cd carer`

`npm install`

## Run app

`node index.js`
