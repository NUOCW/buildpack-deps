FROM nuocw/buildpack-deps:centos7-curl
MAINTAINER "TOIDA Yuto" <toida.yuto@b.mbox.nagoya-u.ac.jp>

RUN yum -y update && yum -y install \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& yum clean all
