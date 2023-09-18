# Redwood RSC Demo 1

Repo demonstrating RedwoodJS' React Server Components implementation

This is the initial example app you get when you first setup RSCs

## How to run

`yarn install`

`yarn rw build -v && yarn rw serve`

## What to do

1. Look at the source and see how the `Counter.tsx` component uses the `'use client'` directive.
2. Notice also that Counter is using `useState`, which is a client-only hook
2. Click on the Increment button and see that client state can be updated
