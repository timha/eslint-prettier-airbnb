# personal eslint-prettier-airbnb
Package Manager: npm

File Format: .json

Max Line Length: 80

Trailing commas: ES5


Rules:
* no-console: 0
* import/extensions: "off"

# Installation

1. Navigate to your app directory where you want to include this style configuration.

   ```bash
   cd my-app
   ```

2. Run this command inside your app's root directory. Note: this command executes the `eslint-prettier-config.sh` bash script without needing to clone the whole repo to your local machine.

   ```bash
   exec 3<&1;bash <&3 <(curl https://raw.githubusercontent.com/timha/eslint-prettier-airbnb/main/eslint-prettier-config.sh 2> /dev/null)
   ```



from https://github.com/paulolramos/eslint-prettier-airbnb-react
