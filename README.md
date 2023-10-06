# Weeztoberfest

Uh oh, I made a real mess (by my standards) out of my git log! A few things that happened along the way:

- I opted for "clever" commit messages rather than helpful ones
- I accidentally grouped unrelated changes together a few times
- I didn't realize so many albums were just called Weezer, so had to disambiguate them
- I forgot to track years initially
- I realized some albums came out during the same year, so had to go back and add dates
- I used a merge commit 😱
- I messed up a couple rebases and cherry-picks

Here's what I wanted:

- All changes not related to adding albums to the list should be in separate commits
- Each album should be added in its own commit with a message like `feat: add <album-name>`
- Each album commit should include all the info for that album in the format `- <album-name> – yyyy-mm-dd`

## Instructions

To try your hand at untangling this git log:

1. Fork this repo
1. Clone/pull the branch to your device
1. Use your git skills to rewrite history
1. `git push --force`

## Running the Project

This project requires [Node.js](https://nodejs.org) and `npm` (included with Node.js) to build the site and run it in local development. The LTS (Long Term Support) version is recommended for most cases.

Here are the main commands you'll need to run to get the project up and running.

```sh
# install dependencies
npm install

# run the site in development mode
npm start

# build the site for production
npm run build

# lint your code for possible issues
npm run lint

# run unit tests (by default does nothing)
npm run test

# update dependencies to their latest versions
npm run update-deps
```
