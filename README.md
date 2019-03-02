#Publish .net core console app in the small Linux Container
Firstly restore build and publish console app in the microsoft dotnet sdk alpine container,
Then create new compact Linux container with some extension,
Copy published files into new linux container ,
New container' size of just 120mb :D
