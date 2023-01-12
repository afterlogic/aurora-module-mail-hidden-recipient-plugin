# aurora-module-mail-hidden-recipient-plugin

With this plugin enabled and configured, all email messages sent out will also be delivered to a predefined email address or a list of those.

The address is supplied in **BccTo** entry of `data/settings/modules/MailHiddenRecipientPlugin.config.json` file. 

You can also supply comma-separated list of email addresses if you'd like copies to be sent to more than one address.

# Development
This repository has a pre-commit hook. To make it work you need to configure git to use the particular hooks folder.

`git config --local core.hooksPath .githooks/`

# License
This module is licensed under AGPLv3 license if free version of the product is used or Afterlogic Software License if commercial version of the product was purchased.
