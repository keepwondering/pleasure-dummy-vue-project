# Dummy project

As an example, will demonstrate the functionality of the pleasure framework in the scenario of an online store.

- [Configuration](#dummy-project-configuration)
- [Entities](#dummy-project-entities)
- [Access & Permissions](#dummy-project-access--permissions)

### Dummy Project Configuration

```js
module.exports = {
  ui: {
    postCssVariables: {
      theme: {
        profile: {
          // accessible via var(--theme-profile-background) in any postcss scope
          background: `green`
        }
      }
    }
  }
}
```

[Read the docs](https://keepwondering.github.io/pleasure)
