```shell
sudo docker build -t yiluxiangbei/chatgpt-shortcut:v1 .
sudo docker run -d -p 8080:80 --name chatgpt-shortcut yiluxiangbei/chatgpt-shortcut:v1
```