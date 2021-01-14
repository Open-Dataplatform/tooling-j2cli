FROM python:3.8-alpine
MAINTAINER Mads Thyssen <mht@energinet.dk>
WORKDIR /app
RUN pip --no-cache-dir install --upgrade pip \
    && pip --no-cache-dir install j2cli[yaml]==0.3.11
ENTRYPOINT ["j2"]
CMD ["--help"]
