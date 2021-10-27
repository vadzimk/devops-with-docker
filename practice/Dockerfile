FROM alpine:3.13
WORKDIR /usr/src/app
COPY hello.sh .
# RUN command is executed during building image
RUN touch additional.txt
RUN chmod +x hello.sh
# CMD command is executed during docker run unless we overrite it
CMD ./hello.sh