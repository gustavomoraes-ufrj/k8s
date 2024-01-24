FROM busybox
WORKDIR /root
COPY  ./scriptdate.sh /root/scriptdate.sh
RUN  chmod +x /root/scriptdate.sh && mkdir  /var/log/
CMD ["sh","/root/scriptdate.sh"]
