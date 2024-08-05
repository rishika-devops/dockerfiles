ARG version
FROM almalinux:${version:-8}
ARG username
RUN adduser $username
USER $username
ARG COURSE
ARG TRAINER
RUN echo "course: ${COURSE} , trainer: ${TRAINER}"
ENV COURSE = ${COURSE}
ENV TRAINER = ${TRAINER}
CMD ["sleep","100"]