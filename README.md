# Test GCP Cloud Run
Test building of docker image for GCP Cloud Run

## Local build
- Copy `.env.example` to `.env`
- `docker build -t laravel-test:latest -f docker/dockerfile .`
- `docker run -p 9051:8080 --env-file .env laravel-test`