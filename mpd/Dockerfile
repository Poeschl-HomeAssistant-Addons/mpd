ARG BUILD_FROM
FROM $BUILD_FROM

RUN apk add --no-cache \
        mpc=0.35-r0 \
        mpd=0.24.4-r1 \
        ympd=1.3.0-r12

ENTRYPOINT [ "/init" ]
CMD []
COPY root /
