Simple OIDC implicit flow tester
================================

This is a bit modified version of the pure JS implementation of an OIDC
client from Django OIDC Provider documentation.

Even though the content is static, it must be served via HTTP, because
browers don't allow redirects to ``file://`` URLs.  You can run the
http-server from npm to serve this by issuing::

  npm install
  npm run serve

Then browse to http://localhost:3000 to check it out.

The original can be found from:

http://django-oidc-provider.readthedocs.io/en/v0.4.x/sections/examples.html#pure-js-client-using-implicit-flow
