# Build Instructions

Simple guide to build your canary versions.

## 1. Build Version A
Build the image using the `app_v1` directory as context. Can be used as version in image, like `my-app:v1` and `my-app:v2`

```bash
docker build -t YOUR_SERVICE_APP_NAME_VERSION_A -f versions/Dockerfile versions/app_v1
```

## 2. Build Version B
Build the image using the `app_v2` directory as context. Can be used as version in image, like `my-app:v1` and `my-app:v2`

```bash
docker build -t YOUR_SERVICE_APP_NAME_VERSION_B -f versions/Dockerfile versions/app_v2
```