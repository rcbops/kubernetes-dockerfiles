FROM alpine:latest
RUN echo "@testing http://nl.alpinelinux.org/alpine/edge/testing" >> /etc/apk/repositories && \
	apk -U --no-cache add file \
	atop \
	htop \
	ltrace \
	strace \
	sysstat \
	bridge-utils \
	ca-certificates \
	iftop \
	iperf \
	iproute2 \
	net-tools \
	nmap \
	tcpdump \
	bash \
	bash-completion \
	gettext \
	logrotate \
	ncurses \
	ncurses-terminfo \
        vim \
        xz \
	zip \
	ncdu \
	hdparm \
	obnam \
	screen \
	pciutils \
	tar \
	tree \
	dstat@testing \
	speedtest-cli \
	psmisc \
	shadow \
	bind-tools \
	curl \
	mtr \
	iotop \
	iputils \
	py-setuptools py-crypto python tzdata \
	pv && \
	easy_install-3.6 pip && \
	pip install ansible && \
        rm -rf /var/cache/apk/*

CMD ["bash"]
