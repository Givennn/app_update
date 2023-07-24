# See .devcontainer/Dockerfile.base and .github/workflows/publish_codespace.yml files.
FROM ghcr.io/givennn/app_update:latest

COPY . /workspace
RUN gem install bundler && \
    bundle install
