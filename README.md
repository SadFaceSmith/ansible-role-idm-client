    ## Roles
Playbooks provided by this repo

### idm-register-ipa-client.yml
Registers an IPA client with an IdM or IPA server.

#### Options
| parameter             | requried | default | comments
|-----------------------|----------|---------|---------
| idm\_server           | yes      |         | The IdM/IPA server to regsiter the IPA client with
| idm\_domain           | yes      |         | The IdM/IPA domain to register the IPA client with
| idm\_enroll\_user     | yes      |         | The IdM/IPA user to enroll the IPA client with
| idm\_enroll\_password | yes      |         | The IdM/IPA password to enroll the IPA client with
| idm\_register\_force  | no       | False   | If `true` and IPA client is already registered it will be unregistered.

