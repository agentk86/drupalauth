# drupalauth

This is a fork of the original project located here: https://code.google.com/p/drupalauth/

The aim of this fork is to provide a drop-in replacement for sites which need
more functionality or flexibility in their IDP.

- - -

## Overview

Drupal + SimpleSAMLphp + drupalauth = Complete SAML Identity Provider (IdP)

Users interact with Drupal to create accounts, manage accounts, and authenticate. SAML SPs interact with SimpleSAMLphp. Drupalauth ties Drupal to SimpleSAMLphp.

The drupalauth module for simpleSAMLphp makes it easy to create a SAML or Shibboleth identity provider (IdP) by enabling authentication of users against a Drupal site on the same server. This allows the administrator to leverage the user management and integration capabilities of Drupal for managing the identity life cycle.

**NOTE:** This is software establishes a SAML identity provider (IdP) using Drupal as the user database instead of LDAP. If you want to establish your Drupal site as a SAML service provider (SP) connected to a SAML or Shibboleth IdP, see the simplesamlphp_auth module for Drupal.

## Installation

Instructions are available at http://code.google.com/p/drupalauth/wiki/INSTALLATION

## License

See LICENSE.txt
