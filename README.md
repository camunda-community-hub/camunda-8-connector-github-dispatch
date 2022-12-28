# GitHub Dispatch Connector

Connect with the GitHub API to [trigger a webhook `repository_dispatch` event](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows#repository_dispatch). 

In this [blog post](https://medium.com/@zelldon91/connecting-camunda-platform-8-with-github-workflows-ee1f91488ad3) I describe how to use the REST connector with Camunda 8 Platform in order to connect with the GitHub workflows. This connector should simplify the configuration and is based on the [REST Connector](https://docs.camunda.io/docs/next/components/connectors/out-of-the-box-connectors/rest/) and allows to send an appropriate POST request to the correct GitHub API, as documented [here](https://docs.github.com/en/rest/repos/repos?apiVersion=2022-11-28#create-a-repository-dispatch-event).

## Element Template

The element templates can be found in the [element-templates/template-connector.json](element-templates/template-connector.json) file.
