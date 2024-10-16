ARG version
FROM almalinux:${version:-9}
ARG course="devops with AWS" \
    duration="120hrs"
ENV duration=$duration    
RUN echo "course: $course, duration: $duration, version: $version"
CMD ["sleep", "100"]    