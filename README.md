# Demo oauth.io -- Retrieve Twitter Timeline

A complete Twitter API access demo.

See <http://blog.hupili.net/oauth.io-demo-twitter/>

## Why

   * <http://oauth.io> is a good integration of OAuth services.
   With the [oauthd](https://github.com/oauth-io/oauthd) source opened,
   I decided to give it a try.
   This simple demo is my own educational material.
   * The official [doc](https://oauth.io/#/docs)
   and [sampl app](http://oauth-io.github.io/oauth-js/)
   only covers auth stage.
   However, there are still many work to do after auth.
   The API designs are different across platforms.
   First timers need to workout the full procedure themselves, which can be frustrating.

## Dependency

   * Auth solution: <git://github.com/oauth-io/oauth-js.git>
   * Twitter RESTful API library in JS: <git://github.com/mynetx/codebird-js.git>
