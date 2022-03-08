# MSAL-SingleAccount-SSO

MSAL sample that shows how to get full SSO. It attempts to get a token silently for the current Windows user, while still working on Mac and Linux.
In order to get full SSO, tenant admin should pre-consent the application, otherwise users will have to consent manually. 

## How to run

This sample is pre-configured with a client ID. Please replace this with your own client ID (under NO circumstance should you use this client ID in production, it is subject to change or to be deleted at any time).


## Other features

- On operating systems without UI, uses device code for interactive authentication
