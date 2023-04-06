# basic-js-code-quality-tools

# Testing with Jest
see [Jest documentation](https://jestjs.io/ru/docs/getting-started)
    
    npm install --save-dev jest

Run tests with `npm test`.


# Formating with prettier
see [Prettier documentation](https://prettier.io/docs/en/install.html)

    npm install --save-dev --save-exact prettier
    echo {}> .prettierrc.json

check [configuration](https://prettier.io/docs/en/options.html)

Use commands `npm run prettier:check` or `npm run prettier:write`.


# Linting with ESLint
see [ESLint documentation](https://eslint.org/docs/latest/use/getting-started)

    npm init @eslint/config

check [rules](https://eslint.org/docs/latest/use/configure/rules)

You can use `eslint:recommended` rules preset or can try [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
To get it `npm install --save-dev eslint-config-airbnb-base` and put it in your `.eslintrc` file `extends` section.

Use commands `npm run lint` or `npm run lint:fix`.

