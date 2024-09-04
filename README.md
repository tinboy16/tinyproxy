# tinyproxy

docker run --name tinyproxy -d -p 8888:8888 -e PROXY_USERNAME=test -e PROXY_PASSWORD=test --restart unless-stopped rootnetworks/tinyproxy:latest
