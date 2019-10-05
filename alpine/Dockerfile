FROM alpine

RUN echo foo
RUN dd if=/dev/zero of=1g1.img bs=1G count=1
RUN dd if=/dev/zero of=1g2.img bs=1G count=1
#RUN dd if=/dev/zero of=1g3.img bs=1G count=1

CMD /bin/true