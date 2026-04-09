FROM gcr.io/oss-fuzz-base/base-builder-go@sha256:9ddab5313bc7053966e80be25f122d6943c0af817d11ec0ad675c2d6b72e703e
COPY . $SRC/atlantis
COPY .clusterfuzzlite/build.sh $SRC/build.sh
WORKDIR $SRC/atlantis
