# character-local-example

Express 4.x app using Character for identity with username and password

## How to test with symlinks

1. Clone this repo
1. Run `npm install`
1. Clone any of the following repos as required:
   1. `character`
   1. `character-authentication`
   1. `character-local`
1. In the folder of each cloned repo, run `npm link`
1. If you have cloned `character-local`, run `npm link character-authenticator`
   in its folder
1. In this repo's folder, run `npm run test-linked`
