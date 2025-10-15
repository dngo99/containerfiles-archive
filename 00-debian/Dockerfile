ARG IMAGE_VERSION
FROM public.ecr.aws/docker/library/debian:$IMAGE_VERSION AS release

ARG IMAGE_DATE
ARG IMAGE_VERSION
LABEL org.opencontainers.image.created="$IMAGE_DATE" \
      org.opencontainers.image.description="Debian is a Linux distribution that's composed entirely of free and open-source software." \
      org.opencontainers.image.title="debian" \
      org.opencontainers.image.url="https://gallery.ecr.aws/docker/library/debian" \
      org.opencontainers.image.version="$IMAGE_VERSION"

ENTRYPOINT [ "/bin/bash" ]
