# Dr. Who API

This project was created with:

- json-server
- heroku

A mock API that details every Doctor and their companion(s) from 2005 to the present. 

I created this project with help from Ania Kubow's tutorial *[Make your own mock API](https://www.youtube.com/watch?v=FLnxgSZ0DG4)*.

## Use this API

Get all Doctors:

`fetch('https://the-dr-who-api.herokuapp.com/doctors').then(response => response.json()).then(data => console.log(data));`

Get all companions: 

`fetch('https://the-dr-who-api.herokuapp.com/companions')`
  `.then(response => response.json())`
  `.then(data => console.log(data));`


