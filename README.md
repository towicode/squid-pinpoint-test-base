# squid-pinpoint-test-base


Instructions:

1. docker build and tag
2. Run with this command `docker run -p 6080:80 -v /dev/shm:/dev/shm <image tag>
3. Access container at http://127.0.0.1:6080/
4. Switch to `wineuser` -> open terminal -> `su wineuser`
5. Use `winetricks` to install c++ 2005
6. Download matlab runtime2015 32bit
7. Use win to install matlab runtime2015

This is where things get a bit dicy

8. use winetricks to install Dotnet 3.5S1
9. use winetricks to install Dotnet 4
10. use winetricks to install vcrun2017

11. Download Ascom Platform https://github.com/ASCOMInitiative/ASCOMPlatform/releases/download/Build_2695/ASCOMPlatform64.exe
12. use win to install Ascom Platform

13. Download pintpoint
14. Run pinpoint like ` wine msiexec /i <pinpoint.msi>`
