FROM nginix:alpine

COPY index.html /usr/share/nginix/html/idex.html

COPY nginix.conf /etc/nginix/nginix.conf

EXPOSE 80

CMD [ "nginix", "-g", "daemon off;"]
