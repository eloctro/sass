# SASS

1. Install SASS:  
   `npm install -g sass`
2. Compile SASS to CSS:  
   `sass source/stylesheets/index.scss build/stylesheets/index.css`
3. Webpack:
   - Install style plugins:  
     `npm install style-loader css-loader sass-loader node-sass extract-text-webpack-plugin -D`
   - Add webpack config for the SCSS
   - Run script
4. Variables:  
   `$proprty-name: value;`

5. Parent selector:
   - & use in nested selectors to refer to the outer selector.
6. Partials & Imports:
   - \_partial.scss + `@import`
7. Mixins:
   - `@mixin name(<arguments...>) { ... }`
   - `@include name();`
8. Extend/Inheritance (placeholders):
   - `@extend + %placeholder`