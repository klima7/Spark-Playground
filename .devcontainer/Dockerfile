FROM apache/spark-py

USER root

RUN useradd -s /usr/bin/bash --create-home vscode

ENV PATH="$PATH:/opt/spark/bin"

RUN pip install pyspark

RUN apt update && apt install -y git

CMD sleep infinity
