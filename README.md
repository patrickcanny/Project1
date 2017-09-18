# Project1
Designing a scheduling client that allows users to create events and designate times available for said events.  We utilized a number of Javascript libraries and functionalities in development of this software. Some of the Libraries we used were:

- DoneJS - https://donejs.com
    DoneJS utilizes a number of embedded libraries such as:

    - CanJS - https://canjs.com
    - Moustache - https://mustache.github.io
    - StealJS - https://stealjs.com

Our choice of framework led us to a component-driven design that is modular and easy to modify. Need to change something only affiliated with the Admin mode? Just go to the admin component folder. In the future, this allows for scalable testing, as individual components can be modified independently.

To get started with our project you'll need to download donejs to your home directory:

`npm install -g donejs`

You'll then need to `cd` into `Plan-EZ` directory. Once in the directory, you'll need to download the dependencies using:

`npm install`

This might take awhile so be patient.

In order to run the project, you'll need to run this while in the `Plan-EZ` directory:

`donejs develop`

This will create the project on a localhost and you'll be able to view the webpage by going to the link that your terminal gives.

Two different modes exist:

1. <b>System Admin Mode</b> allows users to create new calendar events by selecting a date for the event and a set of times that they are available.

2. <b>Adjust Availability Mode</b> allows users to see a list of previously created events and add a set of times that they are available for that event.

We currently plan to use JavaScript to complete this project.
