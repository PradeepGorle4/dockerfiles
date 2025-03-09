# FROM almalinux
# RUN useradd expense
# CMD ["sleep", "100"]

FROM almalinux
RUN useradd expense
USER expense 
# logins the container with expense user instead of root user. Improves the security. Root access is an Absolute NO
CMD ["sleep", "100"]