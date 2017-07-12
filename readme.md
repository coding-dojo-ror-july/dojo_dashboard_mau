Dojo Dashboard
Create a new model called Dojo with the following fields:

branch:string
street:string
city:string
state:string
Using the console, hard code a few records.

Now in the DojosController, index method:

Get all the dojos information
Pass that information to the appropriate view file
Use the .each method to display information of each dojo.

rails g model Dojo branch:string street:string city:string state:string
rake db:migrate
rails c
Dojo.create(branch:'coding dojo', street: '213 w institute st', city:'chicago', state:'illinois')