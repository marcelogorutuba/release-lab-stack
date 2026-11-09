# LAB: stand-in for every umbrella image. Records the build that produced it.
FROM scratch
ARG LAB_RUN
LABEL org.opencontainers.image.source="https://github.com/marcelogorutuba/release-lab-stack" \
      lab.run="${LAB_RUN}"
COPY marker /marker
