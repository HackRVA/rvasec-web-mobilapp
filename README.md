rvasec-web-mobilapp
===================

Webservice interface project for mobile application

Meeting Notes

2013-03-27 through 2013-04-03

We are going to meet to begin more specific design pattern, as well as implementation,  discussions.

Feature Specifications:

1) Get feedback from the intended client, i.e. SecCore/RVASec.

    a) For RVAsec the key features are:

        Provide easy view of the schedule

        Information about the speakers

        Information about the conference

        Information on training

        CTF information

        Ability to provide feedback on the sessions/conference

        Directions to the conference

        Directions to the after party

        Directions address to the hotel

        List sponsors

        Things to do in Richmond that are close (Friday cheers, bars, etc)

        Would be nice if we could “push” news/info to attendees via the app with an alert, notification... lunch is served, snacks are here, beer is available, etc.

        statistics on usage (# of clients, etc), maybe on backed 

    b) SECore (build RVAsec with the frame to use for this which can be a phase 2)

        Take a look at www.secore.info

        SECore wants the ability to have a mobile app that can handle ANY conference and provide all of the current data

        Search all conferences

        Search all CFPs

        Features that are not yet built into the backend are also desired

            find the right conference for you

            rate speakers

            rate talks

            hotel information close to conference

2) Spec the application's primary functionality and architecture

  a) Features

      i) RESTful interface needs to be created for use in interactions between external applications.

        1. .net framework on Arthur's side of the camp

        2. Jax-RS/RestEasy on Martes' side of the camp

        3. Single page design is prefered

  b) platform interface

      i. what interface will this application be attached?

      ii. how best will we communicate with the intended baseurl?

  c) intended language and api

      i. iOS and Android native development (possible phase II)

      ii. simple mobile site for the first iteration (this is phase I)

          1. Determined that html5 with RESTful interface is the most time efficient method of deployment at this time.

          2. Possible caching methods for data persistence.
