<h1>Mini Project Sentiment-Analysis</h1>

URLs for docker images<br>
https://hub.docker.com/r/donglaihe/sentiment-analysis-frontend
https://hub.docker.com/repository/docker/donglaihe/sentiment-analysis-logic

<h3>Steps</h3>

- yarn build
- docker build -f Dockerfile -t $DOCKER_USER_ID/sentiment-analysis-frontend .
- docker push $DOCKER_USER_ID/sentiment-analysis-frontend

- docker build -f Dockerfile -t $DOCKER_USER_ID/sentiment-analysis-logic .
- docker push $DOCKER_USER_ID/sentiment-analysis-logic

- brew install maven
- maven install
- docker build -f Dockerfile -t $DOCKER_USER_ID/sentiment-analysis-web-app .
- docker push $DOCKER_USER_ID/sentiment-analysis-web-app