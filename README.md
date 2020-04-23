# Infrastructure as Code - Starter

## Installation

- AWS account
    ```
    aws configure

    # follow the onscreen instruction for adding access key and access secret
    ```

- Create AWS Cloudformation stack
    
    Network Infrastructure
    ```
    ./create.sh my-network network.yml network-params.json 
    ```

    Servers
    ```
    ./create.sh my-servers servers.yml servers-params.json 
    ```

- Updating AWS Cloudformation stack
    ```
    ./update.sh stack-name stack-file.yml stack-params.json
    ```