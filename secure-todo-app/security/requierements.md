## vamos a poner las mejoras en las los labels de imagenes y lo vamos a meter en una rama que vamos a llamar fix-security-repo

imagen src-client:lates recomendada tag 23-slim

src-backenf tag 23-slim

php imagen da igual el tag

## vulnerabilidades criticas
php
CVE-2022-49043
CVE-2024-56171
CVE-2025-24928
RUN /bin/sh -c set -ex; apt-get update; apt-get install -y --no-install-recommends 
traefik
CVE-2025-22869
CVE-2025-22868
RUN /bin/sh -c set -ex; apkArch="$(apk --print-arch)"; case "$apkArch" in armhf)




