# alpine-gsutil
Alpine Linux Docker Image with gsutil tool

Usage:
``
docker run --rm -v `pwd`:/boto -e BOTO_CONFIG=/boto/boto.cfg idralyuk/alpine-gsutil gsutil ls
``
