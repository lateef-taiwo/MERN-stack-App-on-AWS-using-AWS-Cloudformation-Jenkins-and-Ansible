### MERN Stack  Online Food Ordering App on AWS using AWS Cloudformation, Jenkins, Docker, Kubernetes and Ansible

An online food ordering application built using the Test Driven Development approach with the MERN stack.

### How To Use
To clone and run this application, you'll need [Git](https://git-scm.com/) and [Node.js](https://nodejs.org/en/download/) v15+ (which comes with [npm](https://www.npmjs.com/)) installed on your computer. Also create an account with cloudinary and any mongodb provider, then add required credentials to the `.env` file created from the command below.From your command line:

# Clone this repository
$ git clone https://github.com/lateef-taiwo/MERN-stack-App-on-AWS-using-AWS-Cloudformation-Jenkins-and-Ansible.git food-ordering

# Go into the repository
$ cd food-ordering

# Copy environment variable
$ cp .env.example .env && cp frontend/.env.example frontend/.env

# Install dependencies
$ npm install

# Seed default users and build frontend
npm run heroku-postbuild

# Run the app
$ npm start