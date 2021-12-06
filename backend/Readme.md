# SickFits BackEnd by Kel

Slack community @ <https://app.slack.com/client/T0B6Z0ZL1/C9G96G2UB> Open in safari, already logged in

## Notes/log

npm i needed packages -

changed name to .env from sample.env and added
mongodb connection from Mongo Atlas

watched Intro to GrapQL and setting up KeyStone & TypeScript
created keystone.ts file and added configurations to it
create a User.ts file and added fields to it, in keystone.ts
added a User to 'lists' config, added Auth 'withAuth' stuff
and session field. Then in the dashboard created a user
Josh K email okayknighton@gmail.com abcabcabc for pass

created Product.ts and populated it with fields and such
and added Product in 'lists'. Added ProductImage.ts
and added it to the 'lists' with all Cloudinary connection

### **left off starting on 'Module#4' 17

added a data relationship between ProductImage and Photo
happened in both Product.ts & ProductImage.ts files

Added seed data, in the 'keystone' file inside the DB config
using onConnect. Seed data images are broken.
Changed broken images in localhost:3000 by removing each one
and putting in some photos on 'local' machine.

### **went back to Frontend side, on 'Module#4' 18
