FROM waltermoreira/base-sci-app

MAINTAINER TACC

ENV _APP FastQC
ENV _VERSION ___
ENV _LICENSE GPLv3
ENV _AUTHOR ___

ADD examples.txt /docs/fastqc/examples.txt
ADD usage.txt /docs/fastqc/usage.txt

ADD FastQC /FastQC
RUN ln -s /FastQC/fastqc /usr/bin/fastqc

RUN yum install -y java
