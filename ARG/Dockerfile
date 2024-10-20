ARG version
FROM almalinux:${version:-9}
ARG course="DevOps" \
    duration="120hrs"
ENV duration=$duration
RUN echo "course is $course, and duration is $duration"
CMD [ "sleep", "200" ]