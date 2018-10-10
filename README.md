# aws-ecs-container-login

## Usage

1. `sh ./ssh-aws-ecs-container.sh`
2. Pick the ecs service
3. Pick the ecs task within the ecs service
4. Pick the container name within the ecs task (if there is more than one container defined)
5. aws-ecs-container-login will exec bash inside that container

## Requirements

(can all be installed with Homebrew)

* [aws-cli](https://aws.amazon.com/cli/)
* [jq](https://stedolan.github.io/jq/)
* [peco](https://github.com/peco/peco)

