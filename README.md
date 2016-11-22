
# JavaScript NOW

JavaScript best practises and other collective things

## First meeting's notes

  * päätökset
   * project template: ei -> ohjeistus + esimerkkikoodi
    * mukaan helsinki-spesifit jutut, esim sso ?
   * clojurescript :)
   * eslint airbnb
    * husky pre-commit hook
   * editorconfig?
   * api client
  * tavoitteet
   * ylläpidetäänkö project templatea
    * plus joustava ohjeistus/dokumentaatio
    * npm run build == webpack
    * hot module replacement
    * vs deployaus
  * react-redux-integraatio
   * storen toteutus
    * immutable: ei -> redux free state tms.
   * reselect = ehkä, selektorit = kyllä / normalizr ?
  * vaatimukset
   * API-kutsut
    * client-kirjasto
     * palauttaa promiseja
    * redux-api-middleware
    * saga ?
    * thunk
   * selkeä hakemistorakenne
    * ei tyypin mukaan vaan domaininin
    * case sensitive, default export sama kuin tiedosto
    * src
     * modules
      * user
       * userReducer.js
       * userActions.js ??
       * component.js
       * container.js
       * selectors.js
       * components (dir)
        * componentA.js
       * containers (dir)
        * userListContainer.js
      * place
      * map
   * vähän boilerplatea
    * constants : redux-actions -> ei tarvitse? FSA
   * accessibility / screen readers
    * https://github.com/reactjs/react-a11y
    * testaaminen:
      * selenium
      * living style guide
      * enzyme
      * sinon
      * mocha + chai
      * nightwatch
      * jasmine
      * jest
      * karma
   * react-leaflet
    * ok, mutta ei täydellinen
    * pohdittavaa: leafletien eventtien kytkeminen reduxiin
   * kääntäminen
    * react-intl
    * react-i18next simppelimpi?
   * SEO / Facebook
    * isomorfinen : vaikea
    * sitemapin generointi / API-puolella?
 * mainittua
   * snap ci
  * testaus: gemini : kuvien vertailuun perustuva
   * == living style guide
  * redux form +
  * css modules
  * flow type
  * ramda compose
