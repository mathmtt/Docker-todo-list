FROM betrybe/puppetter:1.0

WORKDIR /app/tests

ADD node_modules.tar.gz .

COPY . /app/tests/

ENTRYPOINT [ "npm" ]

CMD [ "test" ]