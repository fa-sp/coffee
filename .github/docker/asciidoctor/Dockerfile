FROM asciidoctor/docker-asciidoctor:latest

RUN apk add --no-cache \
    openjdk17-jre \
    graphviz

RUN gem install \
    asciidoctor-revealjs \
    asciidoctor-diagram
