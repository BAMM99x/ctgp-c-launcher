# Dockerfile for the bare environment RR needs (dkp tools & necessary libraries installed into /opt). Used in CI

FROM devkitpro/devkitppc:20251231

COPY install-libs.sh ./

RUN ./install-libs.sh
