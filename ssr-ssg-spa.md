<!-- Client Side Rendering  -->

Pros: 
 - fast initial load from server

Const: 
- slow initial load on client(if bundle is big)

<!-- SSR -->

Generates pages on request time.

Can be used instead of SPA for e-commerce when SEO and performance matter;

Pros:
 - content immediately available, because server sends full page hydrated with data
 - no additional requests from client
 - good SEO, because search engine works with fully rendered HTML-page

 Cons: 
 - more load on server
 - incompatible with popular UI-libraries, need to look for alternatives

<!-- SSG -->

Can be used for Blog or public content websites. When it does noes not require a lot of user interaction.

Generates pages at build time(instead of request time like SSR do)

Pros: 
- fast page load(all pages are generated at build stage)
- no additional requests from client

Cons: 
- monolith architecture
- slow rebuild when app growing 
- incompatibility with ui libraries/frameworks 