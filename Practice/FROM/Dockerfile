FROM almalinux:9
RUN dnf install nginx -y
#run instructions run at build image  cmd run at conatiner creation
CMD [ "nginx", "-g", "daemon off;" ]
LABEL course="devops" \
    tariner="Siva kumar" \
    duration="120hrs"
    # labels are add metadata to the images they are usefull in  the image filteration
EXPOSE 80
ENV session="terraform"  \
    trainer="MSR" \
    duration="5hrs"
RUN rm -f /usr/share/nginx/html/index.html
#COPY index.html /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/venkatarajub/terraform-aws-ec2/refs/heads/main/readme.MD /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html



