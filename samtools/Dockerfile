FROM waltermoreira/base-sci-app

RUN yum install -y gcc zlib-devel ncurses-devel
ADD samtools-1.0.tar.bz2 /

WORKDIR /samtools-1.0

RUN make && make install

ADD usage.txt /docs/samtools/usage.txt
