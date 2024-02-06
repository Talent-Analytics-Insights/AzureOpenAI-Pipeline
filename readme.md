# Azure OpenAI API Python Project

## Overview

This Python project is designed to interact with the Azure OpenAI API, providing a resilient connection by implementing a load bearer that switches between multiple resources in the event of a call failure. Additionally, it features functionality to extend the conversation when certain conditions are not met, ensuring a smoother and more robust interaction with the Azure OpenAI services.

## Features
- **Resource Switching**: Automatically switches between predefined Azure resources to maintain consistant performance during API call failures.
- **Conversation Extension**: Extends the conversation flow when specified conditions are not satisfied, enhancing user experience.
- **Easy Configuration**: Simple setup for resource endpoints and condition checks. As an example, a prompt output length condition is shown.

## Prerequisites
- Python 3.x
- Azure OpenAI API keys
- Azure Subscription
