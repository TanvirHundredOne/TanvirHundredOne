# Personal Portfolio
* Built with Jekyll
* Based on gradfoio template
* Needs to add blog site next

<h2> Docker Usage </h2>

# Configure docker container
- inside <code> docker_files</code> directory fetch the <code> Dockerfile</code> and <code>docker-compose.yml</code>. 
- Ensure the <code>pipe</code> the project and <code>/app</code> directory.
- Create docker Image: <code> docker build -t my-ruby-env . </code>
- Docker compose to run the container <code> docker-compose up -d </code>
- You are inside the container now
- cd to /app/project
- run bundle install
- run <code> bundle exec jekyll serve --host 0.0.0.0 --baseurl=""</code>

# Helped by
- <a href='https://dev.to/cuongnp/setting-up-a-local-development-environment-for-jekyll-with-docker-d8k'>Jekyll Image and Container</a>
- <a href='https://stackoverflow.com/questions/53769821/jekyll-site-in-docker-serving-locally'> See docker jekyll from Local</a>

# The Expected File structure
```
├── Dockerfile
├── ReadMe.md
├── TanvirHundredOne.github.io/
├── conf
│   └── nginx.conf
└── docker-compose.yml
```