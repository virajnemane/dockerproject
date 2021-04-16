ARG tag=1.18

FROM nginx:$tag

ARG message="This is my custom nginx image"

RUN echo $message > /usr/share/nginx/html/index.html
