![SendGrid Logo](https://uiux.s3.amazonaws.com/2016-logos/email-logo%402x.png)

[![Travis Badge](https://travis-ci.org/thinkingserious/ibm-sendgrid-live-test.svg?branch=master)](https://travis-ci.org/thinkingserious/ibm-sendgrid-live-test)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE.txt)

**This project allows you to quickly and easily deploy a SendGrid email service utilizing IBM's Cloud Functions.**

* [IBM Cloud Account](http://bit.ly/ibm_cloud_gep)
* [IBM CLI](https://console.bluemix.net/docs/cli/reference/bluemix_cli/download_cli.html#shell_install)
* [SendGrid Account](https://sendgrid.com/free/?source=ibm-index)
* [SendGrid API Key](https://app.sendgrid.com/settings/api_keys)
* [GitHub Account](https://github.com/join)
* [Docker](https://docs.docker.com/install)

<a name="quick-start"></a>
# Quick Start

Go to the [IBM Cloud Functions Actions page](https://console.bluemix.net/openwhisk/actions).

Click the "helloSendGrid" link.

Click the "Parameters" link.

"Add" a parameter with the "Parameter Name" SENDGRID_API_KEY and the "Parameter Value" is your [SendGrid API Key](https://app.sendgrid.com/settings/api_keys). 

```bash
bx wsk action invoke --result helloSendGrid
```
<a name="usage"></a>
# Usage

In addition the [Quick Start](#quick-start), you can access your IBM Cloud Function using CURL.

```bash
cp .env_sample .env
```
