FROM alpine:3.23

ARG TARGETPLATFORM

COPY --chmod=755 $TARGETPLATFORM/tgsearch /app/tgsearch

ENTRYPOINT [ "/app/tgsearch" ]
