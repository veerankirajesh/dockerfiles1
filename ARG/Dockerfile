ARG version
FROM almalinux:${version:-9}
ENV course="docker" \
    duration="5"
ARG trainer="laxmikanth"
ENV trainer=$trainer
RUN echo "Hi, Course is: ${course}, duration is: ${duration}, trainer is: ${trainer}, version: ${version}"
CMD ["sleep", "1000"]