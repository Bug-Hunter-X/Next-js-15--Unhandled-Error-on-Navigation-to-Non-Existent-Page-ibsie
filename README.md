# Next.js 15 Unhandled Error on Navigation to Non-Existent Page

This repository demonstrates a bug in Next.js 15 where navigating to a non-existent page causes an unhandled error, crashing the application.  The issue stems from improper error handling during client-side navigation.

## Bug Description

When attempting to navigate to a page that does not exist, the Next.js application crashes with an unhandled error. This is disruptive to the user experience.

## Solution

The solution involves implementing proper error handling within the application using `Error Boundaries` or other error handling mechanisms to gracefully handle these situations.  This prevents the application from crashing and provides a better user experience.

## How to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Navigate to the `/about` page.
5. Observe the unhandled error that is thrown. 