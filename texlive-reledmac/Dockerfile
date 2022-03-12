FROM dsilakov/rosa-hse
# RUN yum-config-manager --add-repo https://abf-downloads.rosalinux.ru/uartman__personal/repository/
RUN dnf install -y dnf-utils
RUN yum-config-manager --add-repo http://abf-downloads.rosalinux.ru/uartman__personal/repository/rosa2021.1/x86_64/main/release/
RUN dnf install -y texlive-reledmac
ENTRYPOINT rpm -q texlive-reledmac
