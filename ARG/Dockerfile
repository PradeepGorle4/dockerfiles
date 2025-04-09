ARG version
FROM almalinux:${version:-9} 
# :-9 indicates that if user do not provide any version, take 9 as default
ENV course="devops with aws" \
    trainer="siva kumar reddy" \
    duration="120hrs" \
    currentlearning="docker"
ARG name=Pradeep G
# RUN echo "Hello ${trainer}" > /tmp/hello.txt
RUN echo "Hello ${name}, image version: ${version}" > /tmp/hello.txt
CMD ["sleep", "100"]
