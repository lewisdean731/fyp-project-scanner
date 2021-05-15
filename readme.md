# project-scanner

Scans projects in firestore and publishes messages about which ones dependency-scanner should scan 

## Run Locally

```bash
API_ENDPOINT="http://localhost:8080/api" \
API_KEY="dependency-scanner.56a1dcc9-ffd5-430f-a6ab-25c8adf6ab0d" \
PUBSUB_TOPIC_NAME="projects/bu-fyp-s5008913/topics/project-scan" \
RUN_DELAY_SECONDS="30" \
node dist/index.js
```