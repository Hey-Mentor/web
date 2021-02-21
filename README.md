# Hey Mentor app

## Contributing

There are many ways to participate in the project. Just to name a few:

- Submit bugs and feature requests
- Review code changes
- Review documentation and make pull requests for updates

If interested in contirbuting directly to the code, please review the following:

- How to build and run from source:
  1. Make sure you have a GitHub account. If not, [create one](https://github.com/join).
  2. Install [Node.js LTS](https://nodejs.org).
  3. Install [Visual Studio Code](https://code.visualstudio.com/Download) or other editor.
  4. `git clone https://github.com/Hey-Mentor/web hm`
  5. `cd hm`
  6. `npm install`
  7. `gatsby develop`
  8. Open local site at <a href="http://localhost:8000" target="_blank">http://localhost:8000</a>
- Development workflow, including debugging and running tests
  - **Roadmap** – Basic roadmap with high-level themes and features per release.
  - **Iterations** – We work in monthly iterations with small, modest goals.
  - **Planning** – We try to identify what work can be completed before each iteration starts. Each iteration seeks to bring us closer to the next milestone in the roadmap.
  - **Quality** – We strive to attain high quality in everything we do, including consideration for:
    - Accessibility
    - Localization
    - Dark and high contrast mode
- Coding guidelines
- Submitting pull requests
- [Finding an issue](https://github.com/Hey-Mentor/web/contribute) to work on
- Contributing to translations

## Feedback

- Request a new feature
- Upvote existing feature requests
- [File an issue](https://github.com/Hey-Mentor/web/issues/new)
- Follow Hey Mentor on [Twitter](https://twitter.com/heymentornews) or [Instagram](https://instagram.com/heymentor)

## Architecture

Hey Mentor Web uses [React](https://reactjs.org), [Gatsby](https://www.gatsbyjs.com), and [Fluent UI](https://developer.microsoft.com/fluentui).
Here are a few tips for working with each...

### React

Learn more about [React](https://reactjs.org).

### Gatsby

To launch the app locally, run `gatsby develop` and open <a href="http://localhost:8000" target="_blank">http://localhost:8000</a> to test the app or
<a href="http://localhost:8000/___graphql" target="_blank">http://localhost:8000/\_\_\_graphql</a> for the [integrated Graph query tool](https://www.gatsbyjs.org/tutorial/part-five/#introducing-graphiql).

> <small>_Note: If using Edge or Chrome and you see an error about the site not being secure and the browser redirected you to **https**,
> open <a href="chrome://net-internals/#hsts" target="_blank">chrome://net-internals/#hsts</a>,
> scroll down to the **Delete domain security policies** section,
> enter **localhost** into the textbox,
> and click **Delete**._</small>

Edit the code in place and the browser should update automatically (no need to refresh). The default page is `src/pages/index.js`.

Other notable files include:

- **`gatsby-browser.js`**: This file is where Gatsby expects to find any usage of the [Gatsby browser APIs](https://www.gatsbyjs.org/docs/browser-apis/) (if any). These allow customization/extension of default Gatsby settings affecting the browser.
- **`gatsby-config.js`**: This is the main configuration file for a Gatsby site. This is where you can specify information about your site (metadata) like the site title and description, which Gatsby plugins you’d like to include, etc. (Check out the [config docs](https://www.gatsbyjs.org/docs/gatsby-config/) for more detail).
- **`gatsby-node.js`**: This file is where Gatsby expects to find any usage of the [Gatsby Node APIs](https://www.gatsbyjs.org/docs/node-apis/) (if any). These allow customization/extension of default Gatsby settings affecting pieces of the site build process.
- **`gatsby-ssr.js`**: This file is where Gatsby expects to find any usage of the [Gatsby server-side rendering APIs](https://www.gatsbyjs.org/docs/ssr-apis/) (if any). These allow customization of default Gatsby settings affecting server-side rendering.

For more details, refer to the Gatsby [tutorial](https://www.gatsbyjs.org/tutorial) and [documentation](https://www.gatsbyjs.org/docs). In particular, check out the _Guides_, _API Reference_, and _Advanced Tutorials_ sections in the sidebar.

### Fluent UI

Learn more about [Fluent UI](https://developer.microsoft.com/fluentui).
