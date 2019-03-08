# SAML X.509 cert fingerprint

Compute the required fingerprint to connect Keycloak with e.g. GitLab.


## Requirements

* Perl
* OpenSSL


## Usage

Follow this [GitLab Keycloak SAML 2.0 OmniAuth Provider tutorial](https://edenmal.moe/post/2018/GitLab-Keycloak-SAML-2-0-OmniAuth-Provider/) but use `fingerprint` instead, e.g.:

```txt
$ ./fingerprint sample.xml
```
