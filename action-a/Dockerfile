FROM debian:9.5-slim

LABEL "com.github.actions.name"="Hello World"
LABEL "com.github.actions.description"="Write arguments to the standard output"
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="purple"

LABEL "repository"="https://github.com/JCBurnside/hello-github-actions"
LABEL "homepage"="https://github.com/JCBurnside/hello-github-actions"
LABEL "maintainer"="James Burnside (AKA Digital_Light) <jcburnside97@gmail.com>"

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT [ "/entrypoint.sh" ]