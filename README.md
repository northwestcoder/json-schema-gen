# JSON Schema Generator

This project helps you design and validate JSON data models using JSON Schema.

## Setup

1. Install dependencies:
```bash
npm install
```

2. Create your schemas in the `schemas/` directory

## Project Structure

- `schemas/` - Directory containing your JSON Schema definitions
- `examples/` - Example JSON data that validates against your schemas
- `src/` - Source code for any validation utilities

## Example Usage

1. Create a new schema in `schemas/`
2. Validate your JSON data against the schema using the provided utilities
3. Use the schema to generate TypeScript types or documentation

## Dependencies

- [ajv](https://github.com/ajv-validator/ajv) - JSON Schema validator
- [json-schema-ref-parser](https://github.com/APIDevTools/json-schema-ref-parser) - For handling schema references 