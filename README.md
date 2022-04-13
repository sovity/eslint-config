# eslint-config
The holy Ten Commandments for sovity Javascript projects. Follow them or die!

# Using the Config
Install the file 

    npm i -D github:sovity/eslint-config#v1.0
    
Make sure you also install the peer dependencies: 
- ´eslint´
- ´prettier´
- ´eslint-config-prettier´
- ´eslint-plugin-prettier´ 

Include it in your ESLint config.

Write this as part of the configuration object in your `.eslintrc` file:

    "extends": [
        "@sovity/eslint-config/eslint"
    ]

Include the prettier rules.

Write this as the only contents of your `.prettierrc` file:

    "@sovity/eslint-config/prettier"
