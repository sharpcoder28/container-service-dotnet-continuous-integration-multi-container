FROM microsoft/aspnetcore-build:1.0.1
EXPOSE 80

WORKDIR /app
COPY ./bin .

CMD ["dotnet", "service-b.dll"]