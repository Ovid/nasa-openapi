# Unofficial NASA OpenAPI Specification

The official [NASA API website](https://api.nasa.gov/) lists many NASA apis.
Unfortunately, I have not been able to find a clear specification for all of
them, so I've been building an [OpenAPI](https://www.openapis.org/) document,
starting with [api.nasa.gov](https://api.nasa.gov), found in
`nasa/api-nasa-gov/openapi.yaml`.

Currently, you should be able to drop the document into [the online Swagger
Editor](https://editor.swagger.io/) to make it easier to read the document.
You can use the [OpenAPI Generator](https://openapi-generator.tech/) to
automatically build a client for your programming languages of choice.

This project is a work in progress. Only three API endpoints are currently
supported.

# MIT License

Copyright (c) 2023 Curtis "Ovid" Poe

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
