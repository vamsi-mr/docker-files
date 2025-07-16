FROM almalinux:9
CMD [ "google.com" ]
ENTRYPOINT [ "ping" ]

#cmd instruction can be overwritten but we can't overwrite entrypoint if we try to do, it will append or overwrite
#we can use combination of cmd and entrypoint where entrypoint will have command and default args can be supplied by cmd. Here we can always overwrite the default args through command line