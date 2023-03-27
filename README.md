## Setup

### Install all dependencies

```bash
npm i
```

### Environment File

rename the `.env.example` to `.env`.

Enter the access data to connect to your mongodb or mongo atlas

### Github OAuth (optional)

Create a Github OAuth app and copy-paste client id and secret into `.env`.

## Run the application

```bash
npm run dev
```

## Easy Theme Change

If you require a different look, use the skeleton theme generator to modify the `theme.postcss`

## Extend System Language

to add more language just create a new language folder under `src/lib/i18n`. Best to copy de folder with the index.ts file and translate the available content to your needs.

## Create a Data Collection

User Typescript to get all available widget options to create fully custom data structures.
