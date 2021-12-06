# SickFits FrontEnd by Kel

Slack community @ <https://app.slack.com/client/T0B6Z0ZL1/C9G96G2UB> Open in safari, already logged in

## Notes/log

npm i needed packages -

added in /pages a index.js file then account, orders, sell, products
all js files, with a basic <p> tag in them.

created a Page.js in /components and added some elements and PropTypes to it
add _app and_document 'js' files

### **left off starting on 'Module#2' 5

Added Header and Nav js files in /components and link them up
using 'Link'

added styles in Header.js using styledcomponents
then GlobalStyles in Page.js
Implemented NProgress loading bar in _app.js, custom css.
fixed Styled components flicker on SSR in_document.js

### **left off: went to the sickfits/backend

'Module#5' 19 looking at Apollo Client extenstion chrome tool
and looking at the withData.js file and an quick overview of it
"apollo-link-http" apollographql.com docs

add ApolloProvider in '_app.js' and getInitialProps
