# Deploying with CloudFormation

> As your final project, you'll be faced with a real scenario.
>
> Creating this project will give you the hands-on experience you need to confidently talk about infrastructure as code. So, for that reason, we have chosen a realistic scenario where you deploy an application (Apache Web Server) and you also pick up code (JavaScript and HTML) from S3 Storage and deploy it in the appropriate folder on the web server.
>
> There will be two parts to this project:
>
> - You'll first develop a diagram that you can present as part of your portfolio and as a visual aid to understand the CloudFormation script.
> - The second part is to interpret the instructions as well as your own diagram and create a matching CloudFormation script.


## Instructions

To deploy the network stack run

```sh
infrastructure/scripts/create.sh udagram-network-infra infrastructure/cloudformation/stacks/network.yml infrastructure/cloudformation/parameters/network-parameters.json
```

To update the network stack run

```sh
infrastructure/scripts/update.sh udagram-network-infra infrastructure/cloudformation/stacks/network.yml infrastructure/cloudformation/parameters/network-parameters.json
```