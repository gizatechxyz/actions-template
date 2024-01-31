# My Project

This project is generated with a cookiecutter template designed for Giza Actions SDK projects. More in depth documentation can be found [here](https://actions.gizatech.xyz/welcome/giza-actions-sdk).

## Features

- Preprocessing and inference actions defined using Giza Actions SDK.
- Easy deployment and integration with Giza platform.
- Example of an action training a pytorch model and converting it to onnx
- Example of running an action which makes a prediction with the onnx model
- Example of an action which makes a veerifiable prediction with the transpiled model

*Note: examples are based on the [MNIST tutorial](https://actions.gizatech.xyz/tutorials/build-a-verifiable-neural-network-with-giza-actions) and there are steps that must be performed between actions execution like transpiling hte model and deploy the generated model. For more in depth steps check it out*

## Requirements

- Python 3.11
- Giza Actions SDK

## Usage

To use this project, follow these steps:
1. Clone the repository to your local machine.
2. Install the required dependencies.
3. Run any of the provided actions script with the command `python {{cookiecutter.project_slug}}/{action_file}.py`.
