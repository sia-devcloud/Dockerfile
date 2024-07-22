FROM mcr.microsoft.com/dotnet/sdk:8.0
LABEL Author="Shahinur Islam Ahmed"
LABEL Application="nopCommerce"
RUN useradd -d /app -m -s /bin/bash nop
WORKDIR /app
COPY --chown=nop:nop app/ /app
USER nop
EXPOSE 5000
CMD ["dotnet","Nop.Web.dll","--urls","http://0.0.0.0:5000"]