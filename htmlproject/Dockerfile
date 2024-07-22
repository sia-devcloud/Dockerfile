FROM nginx:1.27
LABEL Author="Shahinur"
LABEL Application="html_rent4u"
RUN apt update && apt install unzip -y
ARG DOWNLOAD_URL="https://www.free-css.com/assets/files/free-css-templates/download/page294/rent4u.zip"
RUN curl -O ${DOWNLOAD_URL}
RUN unzip rent4u.zip
EXPOSE 80
RUN mv rent4u-html /usr/share/nginx/html/rentauto