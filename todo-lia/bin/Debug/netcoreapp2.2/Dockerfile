FROM microsoft/dotnet:2.2.100-sdk AS build
WORKDIR /app
COPY . .
CMD echo "Hello world!"
CMD echo "Current dir is $(pwd)"
CMD ls
CMD ls /app

CMD dotnet todo-lia.dll
