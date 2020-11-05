FROM python:3.7-slim
LABEL maintainer="info@practical-devsecops.com"

RUN pip install --upgrade bandit

ENTRYPOINT ["bandit"]
CMD ["-h"]