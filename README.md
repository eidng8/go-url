# go-url

A simple module providing url related functions.

## Functions

`RequestBaseUrl(request *http.Request) *url.URL`

`RequestUrlWithQueryParam(request *http.Request, name string, value string) *url.URL`

`RequestUrlWithQueryParams(request *http.Request, params map[string]string) *url.URL`

`RequestUrlWithoutQueryParams(req *http.Request, params ...string) *url.URL`

`WithQueryParam(u url.URL, name string, value string) *url.URL`

`WithQueryParams(u url.URL, params map[string]string) *url.URL`

`WithoutQueryParams(u url.URL, params ...string) *url.URL`