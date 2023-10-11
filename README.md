# About this repository

This is a simple playground and a sandbox environment for testing the distributed Sumi storage solution using the AWS S3 SDK.

This project is not meant to be comprehensive, but it should contain everything required for getting in.

## Instructions

To use this script, you need a user credential that gives you access to Sumi.
You can read more about it [here](https://sumi-2.gitbook.io/sumi-storage/).

Once you have a valid credential, create a `.env` file with the following content.

```env
AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_DEFAULT_REGION='eu-1'
AWS_ENDPOINT='https://s3.eu-1-ez.flo.stream'

```

Run `yarn` to install all dependencies, and `yarn dev` to run the script locally.

You can edit the `src/app.ts` file for the script behavior.
