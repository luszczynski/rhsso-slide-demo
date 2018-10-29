# Introduction

This is a simple demo showcasing some of RH-SSO features/concepts such as: Realm, Client, Social Login, Themes, etc..

For additional details, please refer to "Additional References section"

## Environment

- [Docker 18.06.1-ce](https://docs.docker.com/install/)
- [Red Hat Single Sign On 7.2](https://access.redhat.com/documentation/en-us/red_hat_single_sign-on/7.2/)
- [Red Hat Single Sign On 7.2 1.2-8 container image](https://access.redhat.com/containers/?tab=security#/registry.access.redhat.com/redhat-sso-7/sso72-openshift/images/1.2-8.1539812404)

## Deploy from DockerHub

- docker pull viniciusmartinez/slide-demo-app:1.0
- docker pull viniciusmartinez/rhsso:1.0

## Building from "Source"

- Clone the application:
```
git clone https://github.com/vinicius-martinez/rhsso-slide-demo.git
```
- Build *(docker build)* RHSSO. Example:
```
cd rhsso
docker build -t viniciusmartinez/rhsso:1.0 .
```
- Build *(docker build)* slide-demo-app. Example:
```
cd slides-app
docker build -t viniciusmartinez/slide-demo-app:1.0 .
```

## Demo Script:

1. [Starting RHSSO and slide-demo-app](#demo-step-1)
2. [Create RHSSO Realm](#demo-step-2)
3. [Create RHSSO Client APP](#demo-step-3)
4. [Create RHSSO Client Roles](#demo-step-4)
5. [Enable SignUp](#demo-step-5)
6. [Change Themes](#demo-step-6)
7. [Authentication Flow](#demo-step-7)
8. [Two Factor with OTP](#demo-step-8)

### Starting RHSSO and slide-demo-app <a name="demo-step-1"></a>
### Create RHSSO Realm <a name="demo-step-2"></a>
### Create RHSSO Client APP <a name="demo-step-3"></a>
### Create RHSSO Client Roles <a name="demo-step-4"></a>
### Enable SignUp <a name="demo-step-5"></a>
### Change Themes <a name="demo-step-6"></a>
### Authentication Flow <a name="demo-step-7"></a>
### Two Factor with OTP <a name="demo-step-8"></a>

## Additional References

[CDK/Minishift Download](https://developers.redhat.com/products/cdk/download/)

[CDK/Minishift Documentation](https://developers.redhat.com/products/cdk/docs-and-apis/)

[CDK/Minishift NodePort](https://access.redhat.com/documentation/en-us/red_hat_container_development_kit/3.6/html-single/getting_started_guide/#nodeport-services)

[Openshift NodePort](https://docs.openshift.com/container-platform/3.10/dev_guide/expose_service/expose_internal_ip_nodeport.html)