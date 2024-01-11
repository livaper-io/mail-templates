# outgoing-templates


## How to use
Firstly, you should add this package to your package.json

`"outgoing-templates": "git+https://bsalperen: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@github.com/livaper-io/outgoing-templates.git#1.0.1"`

After that you should add this to scripts:

`"postinstall": "cp -r node_modules/outgoing-templates/ ./emails" `

## Why we do this?
The `postinstall` script is a special script in Node.js projects that runs automatically after the `npm install` or `yarn install` command finishes. This script is often used for performing setup tasks necessary for the application to run correctly.

The command `cp -r node_modules/outgoing-templates/ ./emails` is a Unix command that copies the outgoing-templates directory from the node_modules folder to the emails directory in the root of your project.
