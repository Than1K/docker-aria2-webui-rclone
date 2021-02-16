mkdir -p /home/aria2/config    # You can put your customized [aria.conf] & [rclone.conf] & [on-complete.sh] into this dir.

mkdir -p /home/aria2/data

docker run --name aria2 -d -p 6800:6800 -p 6880:80 -p 6888:8080 -v /home/aria2/config:/conf -v /home/aria2/data:/data -t aria2-webui-rclone:latest
