# Unofficial NASA OpenAPI Specification

The official [NASA API website](https://api.nasa.gov/) lists many NASA apis.
Unfortunately, I have not been able to find a clear specification for all of
them, so I've been building an [OpenAPI](https://www.openapis.org/) document,
starting with [api.nasa.gov](https://api.nasa.gov), found in
`nasa/api-nasa-gov/openapi.yaml`.

This project is a work in progress. Not all APIs are currently supported. A
[companion project written in Perl](https://github.com/Ovid/webservice-nasa)
is being used to verify these APIs.

Note that those NASA lists numerous APIs, not all of them are hosted on the
same server. More servers will be added later.

# Server `api.nasa.gov`

The `api.nasa.gov` server OpenAPI specification:

* [Raw output](https://raw.githubusercontent.com/Ovid/nasa-openapi/main/nasa/api-nasa-gov/openapi.yaml) (suitable for downloading)
* [Github interface](https://github.com/Ovid/nasa-openapi/blob/main/nasa/api-nasa-gov/openapi.yaml)
* [Redocly](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/Ovid/nasa-openapi/main/nasa/api-nasa-gov/openapi.yaml)

# Server `eonet.gsfc.nasa.gov/api/v3`

The `eonet.gsfc.nasa.gov/api/v3` specification:

* [Raw output](https://raw.githubusercontent.com/Ovid/nasa-openapi/main/nasa/eonet-gsfc-nasa-gov/openapi.yaml) (suitable for downloading)
* [Github interface](https://github.com/Ovid/nasa-openapi/blob/main/nasa/eonet-gsfc-nasa-gov/openapi.yaml)
* [Redocly](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/Ovid/nasa-openapi/main/nasa/eonet-gsfc-nasa-gov/openapi.yaml)

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
