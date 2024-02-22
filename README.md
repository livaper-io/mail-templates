# mail-templates
Update

## How to use
Firstly, you should add this package to your package.json

`"mail-templates": "git+https://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:x-oauth-basic@github.com/livaper-io/mail-templates.git#tag_version"`

After that you should add this to scripts:

`"postinstall": "cp -r node_modules/mail-templates/ ./emails" `

## Why we do this?
The `postinstall` script is a special script in Node.js projects that runs automatically after the `npm install` or `yarn install` command finishes. This script is often used for performing setup tasks necessary for the application to run correctly.

The command `cp -r node_modules/mail-templates/ ./emails` is a Unix command that copies the mail-templates directory from the node_modules folder to the emails directory in the root of your project.
