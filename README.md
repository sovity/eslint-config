# eslint-config
The holy Ten Commandments for sovity Javascript projects. Follow them or die!

# Using the Config
Install the file 

    npm i -D github:sovity/eslint-config

Include it in your ESLint config.

Write this as part of the configuration object in your `.eslintrc` file:

    "extends": [
        "./node_modules/@sovity/style-config/.eslintrc"
    ]

Include the prettier rules.

Write this as the only contents of your `.prettierrc` file:

    "./node_modules/@sovity/style-config/.prettierrc"