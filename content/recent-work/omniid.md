+++
title="Omni ID OAuth 2.0 Provider"
extlink="https://id.omnigroup.com"
imglink="/img/omniid_fullsize.jpeg"
+++

## Description
For Omni ID, we wished to create a single, secure, and predictable login for all of the Omni Group's web services. This involved using the OAuth 2 standard along with the Python oauth-lib library and a custom Django auth backend to create a secure OAuth provider that could authorize users on other valid services either via a username and password or via a token. Myself and another web developer designed this service to allow both web-based clients and native-app clients and for future expansion. Currently, this provider is used for logins to stenciltown2.omnigroup.com service, with future services planned for the future.

## Tools Used
- Python
- Django
- Python OAuth 2 Lib
- Custom Django authentication backend
