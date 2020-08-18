## Work related to the Fulcro  - ReactJS - ecosystem ( omitting the minor and misc contribs )  
 
I’ve documented the learnings and efforts specifically for this project in this YT playlist here .
 
 
https://github.com/fulcrologic/fulcro/pull/337
 
This PR added  (isomorphic) public APIs for dealing with a client-side state management by adding/removing/querying entities in the normalized app-state.
 
Used functional programming, recursion and DB concepts.
 
https://github.com/fulcrologic/fulcro-developer-guide/pull/13
 
This PR helped in rendering the examples in the live Fulcro doc such that they have better anchor tags. It was done by creating a Ruby based pre-processor for the Asciidoc authoring format used by the live documentation. This is the same technique used for Babel compile time plugins.
 
https://github.com/fulcro-legacy/fulcro3/issues/43#issuecomment-519632448  
 
As part of the beta launch for the Fulcro-3.0, I had to parse through the source code in various module in the project.
 
Created a parser and made use of fuzzy string matching to find similarly named public APIs.
 
https://github.com/fulcrologic/fulcro-inspect/pull/78
 
This PR adds optimizations towards rendering 1,000+ elements in the DOM.
 
Relied on refactoring to avoid unnecessary updates across re-renders.
 
 
Work related to pure react
 
I’ve been a fan of Habitica for a long time and I found out that a few Brazilians have created a proper SRS for the project. The problem was it’s only on Brazilian Protuguese. I added support for internationalization, though they are yet to take any action on it so far (I guess, they graduated the Uni and basically abandoned the project or 2020 has kept them occupied anyhow)
 
https://github.com/requisitos-habitica/Habitica/pull/123
 
