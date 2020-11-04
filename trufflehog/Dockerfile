FROM python:3.7-slim
LABEL maintainer="info@practical-devsecops.com"

RUN pip install gitdb2==3.0.0 trufflehog

ENTRYPOINT ["trufflehog"]
CMD ["-h"]