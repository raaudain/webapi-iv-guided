# Deployment Notes

## Quote

> Developers get paid to deliver value, not lines of code
>
> &mdash; A pragmatic developer

## Jargon

_"Single Responsibility Principle"_

Do one thing really well. Only one reason to change.

## Deployment

- extract configuration into environment variables
- setup Continuous Deployment from GitHub to Heroku.
    - commit and push to GitHub and the api gets updated on Heroku
    - add a "start" script to `package.json`
    - make the port dynamic


> ## Git to new repo - Switching Remotes
> `git remote -v`  // shows URL
>
> `git remote set-url origin URL`