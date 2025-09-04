To run program run(git bash for win/terminal for linux):
"dotnet run"
To compile projecct (win) run: 
dotnet publish -c Release -r win-x64 --self-contained true -p:PublishSingleFile=true
To compile project (linux) run:
dotnet publish -c Release -r linux-x64 --self-contained true -p:PublishSingleFile=true
