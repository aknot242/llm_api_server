# LLM API Lab

This lab will walk you through the creation of an API for a locally downloaded AI model.  Then you will step through the process of adding essential security measure to help protect the model's API.

To complete this lab, you will need:

 - access to a container runtime environment, such as [Podman](https://podman.io/) or [Docker](https://docker.com).
 - A [Hugging Face](https://huggingface.co/) account.

## Objective 1 - Test Model in Hugging Face

Test a text summarization model using a Jupyter Notebook and the Hugging Face inference API.

[lab guide](./objective1)

## Objective 2 - Deploy Model Locally

Deploy the text summarization model locally and test using a Jupyter Notebook.

[lab guide](./objective2)

## Objective 3 - Build API for Local Model

Build and deploy a docker container which hosts your local model and API server.

[lab guide](./objective3)

## Objective 4 - Deploy Model API with NGINX

Add NGINX to objective 3 so we can add basic rate limiting.

[lab guide](./objective4)

## Objective 5 - Authorization

Extend objective 4 with API authorization to limit who has access to your model.

[lab guide](./objective5)

## Objective 6 - API Security

Add API security measures to ensure your API is protected against common API-based attacks.

[lab guide](./objective6)