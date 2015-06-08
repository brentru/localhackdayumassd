# Website: Local Hack Day UMass Dartmouth 

Static website created for Local Hack Day (localhackday.mlh.io) at UMass Dartmouth.

### Version
Production Build v1.0.1

### Tech

The Local Hack Day site uses a number of open source projects and technologies to work properly:

Taking the load off the server (we needed to reduce bandwidth/space because we used Divshot's free plan):
* Google Hosted Libs. - usage of hosted library for JQuery
* Boostrap CDN - awesome CDN for hosting bootstrap's internals externally
* Cloudinary CDN - super fast image delivery 

Frontend/Design
* Font Awesome - great fonts for our site
* Twitter Boostrap - frontend design, used for html and most of the css
* ParticleGround - lightweight javascript snippet used to create the interesting particle effects on the schedule page

"Backend" (since this site is static, we didn't use a CMS but used multiple different technologies/solutions to manage it)

* DivShot - fantastic static website hosting
* Cloudflare - ensuring we don't get DDoS'd, server load management
* Google Analytics - metrics for testing/rollout/new features



License
----

MIT


