FROM amazoncorretto:8

RUN yum groupinstall -y "Development Tools"
RUN curl -L -o /usr/bin/bazel https://github.com/bazelbuild/bazelisk/releases/download/v1.7.5/bazelisk-linux-amd64 \
 && chmod +x /usr/bin/bazel
