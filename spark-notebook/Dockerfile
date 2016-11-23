FROM jairamc/spark-kafka-streaming

# Pip
RUN apt-get -y update && \
    apt-get -y install python3-pip && \
    pip3 install --upgrade pip


# Notebook
RUN pip3 install jupyter 

EXPOSE 8888
