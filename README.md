docker build . --tag apk:leaks

docker run -it --rm --network none -v /path/to/shared/dir:/tmp/apkleaks  apk:leaks   -f /tmp/apkleaks/SomeApk.apk
