# Go cross compiler (xgo): Go 1.12
# Copyright (c) 2019 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM registry.cn-hangzhou.aliyuncs.com/youchainhq/xgo:base

LABEL MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 1123

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.12.3.linux-amd64.tar.gz      && \
  export ROOT_DIST_SHA=3924819eed16e55114f02d25d03e77c916ec40b7fd15c8acb5838b63135b03df && \
  \
  $BOOTSTRAP_PURE
