# DevOps_TechTest
Tech Test being done for a Backend / DevOps Role

Current status:

Have a Rails environment, with model for "Message", and an erb view that would display the first Message entry.
With a new entry to that table added to the database through 'rails c', this text would be displayed when running the app ('rails s').

The remaining work to be done is having such app work with the Vagrant box setup and Nginx, which is located in the 'railsbox' folder. The vagrant box is started by running 'vagrant up' in the 'railsbox/development' folder, then 'vagrant ssh'. Currently the box isn't properly provisioned yet to run such app using Nginx.

The work so far has been spiked, so retroactive TDD needs to be done as well.
