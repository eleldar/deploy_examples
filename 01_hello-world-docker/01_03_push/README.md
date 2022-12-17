**Try commands to push:**

* `# docker build -t <username>/hello:v3 .`

* `# docker login -u <username>`

1. `<type username>`
2. `<type password>`

* `# docker push <username>/hello:v3`


**Try next commands to pull:**
* `# docker rmi <username>/hello:v3` 

* `# docker pull <username>/hello:v3`

* `# docker run -it --rm <username>/hello:v3 bash`
