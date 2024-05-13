# How to integrate Sanity in NextJS App Router and access Sanity Studio from the app

## Description

NextJS is a fullstack framework which allows us to develop both frontend and backend altogether seamlessly. It also provides hot reload option so it reloads whenever there is a change in the codebase.

Sanity is a content management system (CMS) which provides generous free tier to encourage developers to come aboard. Also it delivers contents rapidly fast as well as provides CDN services which makes it even faster.

## Start the project

- clone the project
- hope you know which one you are using among them, ```npm```, ```yarn```, ```pnpm```, ```bun```
- install the project from the root folder by ```npm i```, ```yarn```, ```pnpm i```, ```bun i```
- install sanity client globally ```npm install -g @sanity/cli```
- run the sanity initiatializer ```sanity init```
- start the project by ```npm run dev```, ```yarn dev```, ```pnpm run dev```, ```bun run dev```
- okay, so please use only one environment for all the executions, like use only, npm/pnpm/yarn/bun. Mixing would create multiple lockfiles and conflicts.

## From Sanity

- Create an account first on Sanity.
- Start the project and route to ```/studio```
- login from the studio
- create contents and publish

### You need to add the contents manually to show them on the app
