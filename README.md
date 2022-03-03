# Node-Dev-Container
Repo for VSCode Remote Container to work with Nodejs project

## Instruction
- Clone the repo `git clone git@github.com:slier81/Node-Dev-Container.git Node`
- Go inside the created folder `cd Node`
- Change folder owner `sudo chown :9999 -R .devcontainer/docker/{log,vol}`  
- Change folder permission `sudo chmod 775 -R .devcontainer/docker/{log,vol}`  
- Change folder sticky bit `sudo chmod g+s -R .devcontainer/docker/{log,vol}`  
- Create **.env** file `mv .devcontainer/docker/.env.example .devcontainer/docker/.env`  
- Open main folder with VsCode `code .`
