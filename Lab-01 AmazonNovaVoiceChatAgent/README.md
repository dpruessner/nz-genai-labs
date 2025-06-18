# Amazon Nova Voice Chat Agent

Demonstration of using Amazon Bedrock with Nova Sonic LLM to create a web-based voice agent.

This relies heavily on the AWS Samples demonstrating the Nova Sonic LLM and the Amazon Bedrock Agent SDK.

## Prerequisites

- BASH shell to execute deployment scripts
- An AWS account (free to sign up; this project likely will use resources beyond the Free tier)
- AWS CLI installed and configured with your credentials
- Node.js and npm installed
- Nova Sonic LLM access on Amazon Bedrock (see below on how to enable models) [link](#model-access)


## Model Access

To use the Nova Sonic LLM, you need to enable access to the model in your AWS account. Follow these steps:

**1**: Login to your AWS console, search for "Bedrock" and select the service
<img src=".img/01-console.png"></img>

**2**: In the Bedrock console, click on "Models" in the left sidebar (bottom of the left-nav menu)
<img src=".img/02-bedrock-console.png"></img>

**3**: Click on "Enable models" in the top section of the model list
<img src=".img/03-model-access.png"></img>

**4**: In the "Enable models" dialog, select the Nova Sonic model and click "Enable"
<img src=".img/04-sonic-model.png"></img>

**5**: Submit & wait for model to be enabled. This may take a few minutes.
<img src=".img/05-submit.png"></img>

## Acknowledgements

Sample code is largely based on sample code provided by AWS from
[AWS Samples: Amazon Nova ](https://github.com/aws-samples/amazon-nova-samples)
under [MIT License](https://github.com/aws-samples/amazon-nova-samples/blob/main/LICENSE), specifically the `speech-to-speech/repeatable-patterns/resume-conversation` NodeJS project.
