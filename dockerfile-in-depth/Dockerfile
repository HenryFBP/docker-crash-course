FROM debian:jessie
RUN apt-get update && apt-get install -y \ 
  git \
  python \
  vim

COPY foo.txt /src/foo.txt

RUN cat /src/foo.txt

CMD ["python", "-c", "print('hello from python!')"]