# README

## LOCAL QUICKSTART
* build and serve the app:
	`dotnet run`
* then view swagger on localhost: [http://localhost:5000/WeatherForecast](http://localhost:5000/WeatherForecast)


## DEPLOY TO DOCKER
```sh
# build image
docker build -t amandaryman/aspdotnet-api .

# run
docker run --rm -it -p 5000:80 amandaryman/aspdotnet-api

# publish


```
## TO DO

## RESOURCES
* [host an asp.net webapi in docker](https://youtu.be/f0lMGPB10bM)
* [asp.net core 6 web api](https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-6.0&tabs=visual-studio-code)
* [hosting asp.net core apps in docker](https://learn.microsoft.com/en-us/aspnet/core/host-and-deploy/docker/?view=aspnetcore-6.0)
* [asp.net docker examples](https://github.com/dotnet/dotnet-docker/tree/main/samples/aspnetapp)
* [swagger](https://aka.ms/aspnetcore/swashbuckle)