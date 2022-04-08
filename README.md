# PackageManagementCheatSheet
Do you find yourself maintaing packages across a variety of systems? Remember the basics with this cheat sheet!

 | System     	| Update      	| Install                         | Remove                        | Upgrade                     	|
|------------	|-------------	|----------------------------------	|------------------------------	|-----------------------------	|
| Apt        	| apt update  	| apt install *package*           	| apt remove *package*         	| apt upgrade                 	|
| Chocolatey 	|             	| choco install *package*        	  | choco uninstall *package*    	| choco upgrade               	|
| Docker     	|             	| docker pull *package*             | docker rm *container*        	| docker update *container*     |
| Flatpack   	|             	| flatpak install *repo* *package*  | flatpack uninstall *package* 	| flatpack update             	|
| Homebrew   	| brew update 	| brew install *package*            | brew remove *package*        	| brew upgrade                	|
| Git        	|             	| git clone *url*                   | rm -rf *repo_directory*? 😅   | git remote add upstream *url* |
| Pacman     	| pacman -S   	| pacman -S *package*            	  | pacman -R *package*          	| pacman -Syu                 	|
| Snap       	|             	| snap install *package*            | snap remove *package*        	| snap refresh                	|
