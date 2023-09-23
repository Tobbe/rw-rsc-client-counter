# Redwood RSC Demo 1

Repo demonstrating RedwoodJS' React Server Components implementation

This is the initial example app you get when you first setup RSCs

## How to run

### GitPod

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/from-referrer/)

### Locally

`yarn install`

`yarn rw build -v && yarn rw serve`

## What to do

1. Look at the source and see how the `Counter.tsx` component uses the `'use client'` directive.
2. Notice also that Counter is using `useState`, which is a client-only hook
2. Click on the Increment button and see that client state can be updated

## List of Redwood RSC demos

 1. https://github.com/Tobbe/rw-rsc-client-counter
 2. https://github.com/Tobbe/rw-rsc-suspense
 3. https://github.com/Tobbe/rw-rsc-server-mutation
 4. https://github.com/Tobbe/rw-rsc-rsf-return-value
 5. https://github.com/Tobbe/rw-rsc-form-server-action
 6. https://github.com/Tobbe/rw-rsc-ai-jsx
