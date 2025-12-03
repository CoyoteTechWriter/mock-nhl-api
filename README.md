# NHL Mock API – OpenAPI 3.0

A clean, fully documented mock REST API for NHL players.  
This is done solely for the purpose of portfolio. I do not wish to make profit nor do I hold any rights to NHL products.

### Live Interactive Documentation
- The NHL mock API was designed on SwaggerHub, with no use of AI tools
- [SwaggerHub version: https://app.swaggerhub.com/apis/YOUR-USERNAME/nhl-api-v1/1.0](https://app.swaggerhub.com/apis/none-2ef-05d/nhl-api-v1/1.0)

### Features
- OpenAPI 3.0.2
- Reusable components & query parameters
- Realistic validation rules (playerID pattern, jersey number max 2 digits, etc.)
- GET and POST methods (with proper summaries, descriptions and references)
- Schemas and parameters populated with strings, integers, regular expression patterns, etc.

### Reasoning

I decided to use string for jersey numbers, because this allows regular expression use for patterns.
The 'reusable' include schemas and properties since I wanted to showcase my knowledge of OAS best practice.

### Quick start
Open the yaml file in this repo → click “View API docs” and try it!

Built to demonstrate clean API design — no backend required.
