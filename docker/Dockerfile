FROM python:3.10.11-bullseye

WORKDIR /app

COPY . ./

RUN pip --version && \
    export mirror_url="https://mirrors.bfsu.edu.cn/pypi/web/simple/" && \
    python3 -m pip install -i ${mirror_url} --upgrade pip && \
    pip3 config set global.index-url ${mirror_url} && \
    pip install -r requirements.txt

CMD [ "/bin/bash" ]
