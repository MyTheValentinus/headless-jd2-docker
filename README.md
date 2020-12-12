# MyJDownloader

This docker image work but i recommand you this image: https://github.com/jlesage/docker-jdownloader-2

## Running the container
```docker run -d --name jd2 -v /config/jd2:/opt/JDownloader/cfg -v /home/user/Downloads:/root/Downloads -e JDEMAIL=yourmail@mail -e JDPASSWORD=yourpassword -e JDDEVICENAME=yourdevicenameinmyjd mythevalentinus/myjdownloader-docker```
