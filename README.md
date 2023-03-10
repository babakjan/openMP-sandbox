# Open MP sandbox

Sandbox for running C, C++ project with openMP dependency in docker.

## Get repository

```bash
git clone https://gitlab.fit.cvut.cz/babakjan/openmpsandbox.git
cd openmpsandbox
```

## Build container

```bash
docker build -t openmpsandbox .
```

## Run container

```bash
docker run -it -v `pwd`:/work openmpsandbox
```

## Run main.cpp in terminal
```bash
make run
```

## Run main.cpp in VS code

-   Install extension [Dev containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

-   Run remote development
    -   Open development environment
        <img src="./images/start-remote-development.png" title="Start remote development"/>
    -   install extensions in Remote development [C, C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools), [makefile](https://marketplace.visualstudio.com/items?itemName=ms-vscode.makefile-tools)
    -   Configuration
        <img src="./images/configuration.png" title="Configuration" />
    -   Target
        <img src="./images/target.png" title="Target" />
    -   Launch
        <img src="./images/launch.png" title="Launch" />
