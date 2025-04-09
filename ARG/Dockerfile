ARG version
FROM almalinux:${version:-9} 
# :-9 indicates if user does not provide version takes 9 as default. Also the 1st ARG given before FROM will only work till FROM
ENV course="devops with aws" \
    trainer="siva kumar reddy" \
    duration="120hrs" \
    currentlearning="docker"
ARG name=PradeepG
# if you want to set ARG to be accessible inside container, just do the below
ENV name=${name}
# RUN echo "Hello ${trainer}" > /tmp/hello.txt
RUN echo "Hello ${name}, image version: ${version}" > /tmp/hello.txt
CMD ["sleep", "100"]
