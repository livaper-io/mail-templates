# mail-templates

## How to use
Firstly, you should add this package to your package.json

`"mail-templates": "github.com/livaper-io/mail-templates.git"`

After that you should add this to scripts:

`"postinstall": "cp -r node_modules/mail-templates/ ./emails" `

## Why we do this?
The `postinstall` script is a special script in Node.js projects that runs automatically after the `npm install` or `yarn install` command finishes. This script is often used for performing setup tasks necessary for the application to run correctly.

The command `cp -r node_modules/mail-templates/ ./emails` is a Unix command that copies the mail-templates directory from the node_modules folder to the emails directory in the root of your project.
