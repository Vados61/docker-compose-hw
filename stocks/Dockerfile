FROM python:3.9

WORKDIR src

COPY requirements.txt /src/requirements.txt
RUN pip3 install --no-cache-dir --upgrade -r /src/requirements.txt

COPY . /src


ENTRYPOINT ["/src/entrypoint.sh"]