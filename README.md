# GitHub dispatch connector

Connect with the GitHub API to [trigger a webhook `repository_dispatch` event](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows#repository_dispatch). 

In this [blog post](https://medium.com/@zelldon91/connecting-camunda-platform-8-with-github-workflows-ee1f91488ad3) I describe how to use the [REST Connector](https://docs.camunda.io/docs/next/components/connectors/out-of-the-box-connectors/rest/) with Camunda 8 Platform in order to connect with GitHub workflows. This GitHub Dispatch connector should simplify the configuration and is based on the [REST Connector](https://docs.camunda.io/docs/next/components/connectors/out-of-the-box-connectors/rest/) and allows to send an appropriate POST request to the correct GitHub API, as documented [here](https://docs.github.com/en/rest/repos/repos?apiVersion=2022-11-28#create-a-repository-dispatch-event).

## How to use

In order to use the connector template with your [Desktop Modeler](https://camunda.com/download/modeler/), copy the element template [github-dispatch-connector.json](https://github.com/camunda-community-hub/camunda-8-connector-github-dispatch/blob/main/element-templates/github-dispatch-connector.json) to your resources folder either next to your modeler executable or to your BPMN model files. For more information [read the corresponding documentation](https://docs.camunda.io/docs/next/components/modeler/desktop-modeler/element-templates/configuring-templates/#:~:text=Store%20element%20templates,diagram%27s%20path%20hierarchy). In Camunda Platform 8 SaaS we will hopefully support this connector soon as well.

If the template is available in your modeler you can choose it in the corresponding templates menu. If the GitHub dispatcher connector template is picked the related properties panel will look similar to this:

![template](https://user-images.githubusercontent.com/2758593/209766946-055c9b3f-f8ee-4cc8-9118-a60ec95ce1ee.png)

Follow this [blog post](https://medium.com/@zelldon91/connecting-camunda-platform-8-with-github-workflows-ee1f91488ad3) to set the correct details.

## Element Template

The element template can be found in the [element-templates/github-dispatch-connector.json](https://github.com/camunda-community-hub/camunda-8-connector-github-dispatch/blob/main/element-templates/github-dispatch-connector.json) file.
