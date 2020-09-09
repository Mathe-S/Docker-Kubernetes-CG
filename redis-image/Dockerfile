#Use an existing docker image as a base
FROM alpine

#Donwload and install a dependency
RUN apk add --update redis

#Tell th eimage what to do when it starts as a container
CMD ["redis-server"]