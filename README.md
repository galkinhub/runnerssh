# SSH to a gitlab runner
Note: see .github/workflows .yml file dot specific commands 
* Run a reverse_ssh server
* instruct it to compile client for wanted OS+platform (6 example commands given)
* Run github action, manually edit parameters to specify ip:port to your reverse-ssh server, and wanted runner
* Wait until it connects back, notice host name in reverse_ssh server log
* connect to that server using reverse_ssh as a jump sever
* terminate your runner session when done via `killall exe.exe` or `taskkill /F /IM exe.exe` or via github interface

Windows/linux/mac supported including both x86_64 and arm64 variants.

Great thanks to https://github.com/NHAS/reverse_ssh project for implementing 99% of base functionality
