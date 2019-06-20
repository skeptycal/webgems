23:29 $ npm audit

      === npm audit security report ===

Run  `npm update tar --depth 3`  to resolve 1 vulnerability
┌───────────────┬──────────────────────────────────────────────────────────────┐
│ High          │ Arbitrary File Overwrite                                     │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ tar                                                          │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ node-sass [dev]                                              │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ node-sass > node-gyp > tar                                   │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://npmjs.com/advisories/803                             │
└───────────────┴──────────────────────────────────────────────────────────────┘


found 1 high severity vulnerability in 14608 scanned packages
  run `npm audit fix` to fix 1 of them.

23:30 $ npm audit fix
updated 1 package in 5.34s
fixed 1 of 1 vulnerability in 14608 scanned packages

23:30 $ npm audit

      === npm audit security report ===

found 0 vulnerabilities
 in 14608 scanned packages
