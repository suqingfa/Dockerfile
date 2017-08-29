#
# Node.js Bower & Grunt Dockerfile
#

FROM library/node:slim

MAINTAINER suqingfa enmoton@qq.com

RUN apt-get update && apt-get install -y git && apt-get clean
RUN npm install -g bower grunt-cli && echo '{ "allow_root": true }' > /root/.bowerrc

WORKDIR /data

CMD ["bash"] 