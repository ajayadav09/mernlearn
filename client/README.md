# client-side
React/Redux

# Usage(make it run on your machine)

## Client-side usage(PORT: 3000)
```terminal
$ cd client   // go to client folder
$ yarn        // npm install packages
$ yarn dev    // run it locally

// deployment for client app
$ yarn build // this will compile the react code using webpack and generate a folder called docs in the root level
$ yarn start // this will run the files in docs, this behavior is exactly the same how gh-pages will run your static site

// use parcel to run
$ yarn dev:parcel
```

# Some screenshots

User visit public and Home page
![User visit public and Home page](http://i.imgur.com/ORCGHHY.png)

User can sign in or sign up
![User can sign in or sign up](http://i.imgur.com/rrmbU5I.png)

After signing in user can go to account page and make request to token-protected API endpoint
![After signing in user can go to account page](http://i.imgur.com/FzLB51u.png)

## Bugs or comments
[Create new Issues](https://github.com/ajayadav09/mern/issues)

## Author
[ajayadav09](ajayadav09.github.io)
- Feel free to find me on _[GitHub](https://github.com/ajayadav09)_ and _[LiveCoding](https://www.livecoding.tv/ajayadav09/)_
- or visit my _[page](http://ajayadav09.github.io/)_

### License
[MIT](https://github.com/ajayadav09/eventbrite-api/blob/master/LICENSE)


### TODO
- Remove webpack
- Add env for deployment .env.dev .env.prod