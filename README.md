This is the code from the youtube Tut MEAN Stack Front To Back from Traversy Media.

Currently I'm stuck in lecture 9. after running the code  I get the final Error message in the Terminal: 
----------------------------------------------------------------------------------------------------------------
webpack: Compiling...
Hash: 16de45009934f6595cd5                                                         
Time: 1852ms
chunk    {0} polyfills.bundle.js, polyfills.bundle.map (polyfills) 234 kB {4} [initial]
chunk    {1} main.bundle.js, main.bundle.map (main) 27.8 kB {3} [initial]
chunk    {2} styles.bundle.js, styles.bundle.map (styles) 9.71 kB {4} [initial]
chunk    {3} vendor.bundle.js, vendor.bundle.map (vendor) 2.98 MB [initial]
chunk    {4} inline.bundle.js, inline.bundle.map (inline) 0 bytes [entry]

ERROR in /Users/younessouannani/meanauthapp/angular-src/src/app/services/auth.service.ts (3,39): Cannot find module '@angular/common/http'.

ERROR in /Users/younessouannani/meanauthapp/angular-src/src/app/components/profile/profile.component.ts (16,27): Property 'user' does not exist on type 'Response'.

ERROR in ./src/app/services/auth.service.ts
Module not found: Error: Can't resolve '@angular/common/http' in '/Users/younessouannani/meanauthapp/angular-src/src/app/services'
 @ ./src/app/services/auth.service.ts 12:0-51
 @ ./src/app/app.module.ts
 @ ./src/main.ts
 @ multi webpack-dev-server/client?http://localhost:4200/ ./src/main.ts
webpack: Failed to compile.


----------------------------------------------------------------------------------------------------------------


Your help is very much appreciated!!!










































