FROM alpine

LABEL maintainer="eldegor <eldegor1980@gmail.com>"

ADD pythongame.tar.gz /

RUN apk add python3 py3-pip 
	#&& pip3 install uvicorn fastapi jinja2 python-multipart

WORKDIR /python-textovka


CMD [ "/usr/bin/env", "python3", "/python-textovka/game.py" ]

