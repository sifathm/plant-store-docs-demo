# Plant Store API Docs

This is a demo documentation site I built for a mock Plant Store API using Fern + OpenAPI. The goal was to create something that feels clean, easy to navigate, and actually useful if you were a developer trying to use the API.

## What this is

The API lets you manage plants, search inventory, and handle basic user actions. The docs are meant to make it really straightforward to understand how everything works without digging through messy specs.

## What I included

- Full API reference with endpoints like `/plant`, search routes, and user auth
- A webhook (`plant.created`) with a real example payload
- A Python code sample for `POST /plant` using requests
- Production + Sandbox environments set up in the API
- A custom landing page instead of the default template
  
## Project structure

- fern/api.yml
- fern/docs.yml
- fern/fern.config.json
- fern/docs/pages/landingpage.mdx
- fern/docs/pages/instructions.mdx


## Running it locally

npm install -g fern-api  
fern docs dev  

Then open http://localhost:3000

## Live site

https://sifath-mannan-demo.docs.buildwithfern.com

## If I had more time

I’d add more sections to the landing page so it feels a bit more complete and improve navigation between sections. I’d also expand the API explorer with more edge cases and examples.

## Notes

This was my first time using Fern, so a lot of this was learning how the docs and OpenAPI pieces fit together. It gave me a better sense of how developer documentation should actually feel to use.
