Docker build for ReadTheDocs (RTD)
================================

This repository provides Dockerfile for [Read The Docs][0] 

### Status
Built images are uploaded to [index.docker.io][1]

### Usage:

 - Install Docker: [http://docs.docker.io/][2]
 - Execute
 `docker run -d --name ReadTheDocs -p 8000:8000 shaker/readthedocs`
 - Browse [http://&lt;your server ip address&gt;:8000/][3]
 - Stop and start again
   - `docker stop ReadTheDocs`
   - `docker start ReadTheDocs`
 - username/password for admin:
   - `username` is `admin`
   - `password` is `admin`

  [0]: http://readthedocs.org
  [1]: https://index.docker.io/u/shaker/
  [2]: http://docs.docker.io/en/latest/ "docs.docker.io"
  [3]: http://127.0.0.1:8000/
