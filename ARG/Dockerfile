ARG version
FROM almalinux:${version:-9}
ENV course="DEvops with AWS" \
    trainer="shiva" \
    duration="120hrs" 
#here user1 is key,someuser is default value
ARG USERNAME=Leela
ENV USERNAME=$USERNAME
RUN echo "Hello User: ${USERNAME}" > /tmp/devops.txt 
CMD ["sleep","100"]