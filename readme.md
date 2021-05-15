# project-scanner

Scans projects in firestore and publishes messages about which ones dependency-scanner should scan 

## Install
```bash
npm install
```

## Run Locally

```bash
npm run compile
```

```bash
API_ENDPOINT="http://localhost:8080/api" \
API_KEY="addAPIkeyHere" \
PUBSUB_TOPIC_NAME="projects/bu-fyp-s5008913/topics/project-scan" \
RUN_DELAY_SECONDS="30" \
node dist/index.js
```