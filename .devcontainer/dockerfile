# اختر صورة Ubuntu الأساسية
FROM ubuntu:24.04

# تحديث النظام وتثبيت الحزم الأساسية
RUN apt-get update && apt-get upgrade -y \
    && apt-get install -y \
        git \
        curl \
        python3 \
        python3-pip \
    && rm -rf /var/lib/apt/lists/*
