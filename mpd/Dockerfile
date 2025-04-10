ARG BUILD_FROM
FROM $BUILD_FROM

RUN apk add --no-cache \
        mpc=0.35-r0 \
        mpd=0.23.16-r0 \
        ympd=1.3.0-r12

ENTRYPOINT [ "/init" ]
CMD []
COPY root /
