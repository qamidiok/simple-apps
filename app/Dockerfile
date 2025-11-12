FROM node:18.16
RUN apt update -y
WORKDIR  /app
ADD . /app
LABEL author="deni@idn.id"
EXPOSE 3000
CMD ["npm","start"]