# Quickstart

Starting using js-spider is simple as 1-2-3

## Sign up (1)

No payment required, after signing up you'll get a starter account plan,
capable of anything up until you reach the cap of 1000 errors catched.

It would be more than enough for you to get comfortable with js-spider.

You can use GitHub, Google or Facebook account to sign up.
Also, there is an option for the good old e-mail authorization, if you wish.

<a href="https://js-spider.com/" target="_blank">Sign Up</a>

or

<a href="https://js-spider.com/login" target="_blank">Sign In</a>

## Create a new project (2)

Log in to your account and create your first project on our board. Link it to the domain you're want to use it for,
to get a `projectId`

If there is no domain, such as when you're using Cordova or something similar, there would be a private `accessKey`
for you.

Errors from multiple development and production environments wouldn't mix together —
instead, they would be separated into subfolders, which are customizable by you.

## Use our script with your projectId (3)

Once you've created your account and got a projectId, you'll need to
install our script either for the browser (frontend) or for the Node.js backend.

#### Browser

Add this to your website code to start using js-spider:

```html
<!-- JavaScript error monitoring agent. More on js-spider.com -->

<script src="https://js-spider.com/js/js-spider.js"></script>
<script>
    JsSpider.init({ projectId: 'xxxxxx-xxxx-xxx-xxxx' });
</script>

<!-- /JavaScript error monitoring agent. More on js-spider.com -->
```

Or, take a dependency on our [browser npm package](https://www.npmjs.com/package/@ayast/js-spider-browser)

#### Backend

Using usual JavaScript require syntax:

```javascript
const JsSpider = require('@ayast/js-spider-backend');
```

TypeScript imports:

```typescript
// Option 1: CommonJS import, preferred by Node.js
import JsSpider = require('@ayast/js-spider-backend');

// Option 2: ES6 import
import * as JsSpider from '@ayast/js-spider-backend';
```

Usage:

```js
// TODO: How to use with backend Node.js
```

## That's it, folks!

Now, js-spider logs and catches all the errors from your project!
