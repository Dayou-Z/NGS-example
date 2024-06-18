FROM ubuntu
RUN apt-get update && apt-get install -y git build-essential zlib1g-dev libbz2-dev liblzma-dev
WORKDIR /tmp
RUN git clone --recursive git://github.com/ekg/freebayes.git
WORKDIR freebayes
RUN make 
RUN make install
ENTRYPOINT ["freebayes"]
