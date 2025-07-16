ARG version
FROM almalinux:${version:-9}
ENV course="devops"
ARG trainer="siva"
ENV trainer=$trainer
RUN echo "HI, course is: ${course}, trainer is: ${trainer}"
CMD ["sleep", "1000"]
