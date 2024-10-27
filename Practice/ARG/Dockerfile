ARG version
FROM almalinux:${version:-9}
# ARGs (arguments) are used provide the variables  and  at build time.
ARG course="Devops with AWS" \
    duration="130hrs"
ENV duration=$duration
RUN echo "course is $course and duration is $duration"
CMD [ "sleep", "100" ]

#how  can you use  ARG at run time?
# By setting arg value to ENV variable. 