FROM mcr.microsoft.com/dotnet/aspnet:6.0
COPY LearnApi/LearnApi/bin/Debug/net6.0/publish/ App/
WORKDIR /App
ENTRYPOINT [ "dotnet", "LearnApi.dll" ]