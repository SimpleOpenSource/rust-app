# Rust App

Web application built in rust with database interaction.
- [Live Here](https://sos-rust-app-api.shuttleapp.rs)

* Backend build with [Actix Web](https://actix.rs/) framework and deployed on [Shuttle](https://www.shuttle.rs/)

## For developpers
1. Launch docker
2. cargo shuttle run (if commands fail because of os error 13, make sure current user is in docker group. [See doc](https://phoenixnap.com/kb/docker-permission-denied))

### Frontend
Go to folder /front and in seperate terminals launch the following commands
1. npx tailwindcss -i ./input.css -o ./public/tailwind.css --watch
2. dx serve --port 8000


# Deployment to shuttle
launch the following commands to build and deploy the project
1. makers
2. cargo shuttle deploy
