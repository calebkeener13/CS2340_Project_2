# Spotify Wrapped Web Application
(Forked from [Original Repo](https://github.com/Wilsdawg1212/2340_Project_2.git))

## Overview

This project is a Spotify Wrapped web application that allows users to log in with their Spotify account and view personalized music insights, such as top tracks, artists, genres, and suggested playlists. Additionally, users are able to choose what the teme and time range for their wraps are as wellIt was developed as part of a team project for CS 2340.

## My Role & Contributions

I was actively involved in:
- **Frontend Development**: Implemented [specific feature, e.g., the dashboard UI using Bootstrap 4.3.1].
- I was responsible for the **backend integration**, specifically implementing the **entire user registration logic flow**. This included:

  - Designing and implementing the **Spotify OAuth2 authentication system** to allow users to securely link their Spotify accounts.
  - Ensuring smooth user login and registration processes.
  - Managing OAuth tokens and handling the callback flow to retrieve user data from Spotify.
  - Designing the backend logic flow allowing users to delete their account from the application
- **Database Design**: Designed the CustomUser model that housed all the pertinent information for the users including spotifyID, user tokens, email, username, password, etc. Also created the wrap model and progressibely updated the model overtime to be able to meet the information demands of the wraps. Example fields for this model include, top_artist, top_album, top_genre, theme, etc.
- **Feature Development**: Worked on the feed page for this application. This page displays all the public wraps made by users on this application, and the user can like wraps and filter these wraps by the ones that they have liked. Additionally, the user can regenerate any wrap that is on the feed page to see how it would look like in wrapped form. 

## Technologies Used

- **Django** (Python web framework)
- **Spotify Web API**
- **JavaScript & jQuery**
- **Bootstrap 4.3.1** for responsive UI design
- **SQLite** for data storage during development

## Purpose of the Fork

This fork was created to display my contributions to the project and demonstrate my work as part of a collaborative effort in a real-world software development environment.
