FROM python:3.7-slim
LABEL maintainer="info@practical-devsecops.com"

RUN pip install --trusted-host pypi.python.org safety

WORKDIR /src
ENTRYPOINT ["safety"]
CMD ["-h"]