# Test GCP Cloud Run
Test building of docker image for GCP Cloud Run
- `docker build -t laravel-test:latest -f dockerfile .`
- `docker run -p 9051:80 laravel-test`