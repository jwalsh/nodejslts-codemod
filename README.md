# nodejslts-codemod

Audit projects with jscodeshift targeting LTS (i.e., Node.js 4.2 (Argon) to 6.0) 

# Setup 

    npm i -g jscodeshift

# Development 

    npm test

# Testing 

     ./node -pe process.versions
     { http_parser: '2.7.0',
      node: '6.0.0',
      v8: '5.0.71.35',
      uv: '1.9.0',
      zlib: '1.2.8',
      ares: '1.10.1-DEV',
      modules: '48',
      openssl: '1.0.2g' }

# Background

- https://nodejs.org/en/blog/release/v5.0.0/
- https://github.com/nodejs/node/issues/5766
