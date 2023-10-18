# Step Name -> Go B64 Code
## Component Denominator -> json-generator-connector

## Component Description

JSON Generator (Mock) creates a JSON object. This component accepts any input.

Check this component official documentation: [json-generator-connector](https://docs.digibee.com/documentation/components/tools/json-generator "Digibee json-generator-connector documentation")

## Component Configuration Details
### Documentation



### Parameters

* JSON
The json to generate. Double braces expressions are allowed.

```
{
    "b64code": "cGFja2FnZSBtYWluCgppbXBvcnQgKAoJImVuY29kaW5nL2pzb24iCgkiZm10IgopCgovLyBUaGUgc2FtZSBqc29uIHRhZ3Mgd2lsbCBiZSB1c2VkIHRvIGVuY29kZSBkYXRhIGludG8gSlNPTgp0eXBlIEJpcmQgc3RydWN0IHsKCVNwZWNpZXMgICAgIHN0cmluZyBganNvbjoiYmlyZFR5cGUiYAoJRGVzY3JpcHRpb24gc3RyaW5nIGBqc29uOiJ3aGF0IGl0IGRvZXMiYAp9CgpmdW5jIG1haW4oKSB7CglwaWdlb24gOj0gJkJpcmR7CgkJU3BlY2llczogICAgICJQaWdlb24iLAoJCURlc2NyaXB0aW9uOiAibGlrZXMgdG8gZWF0IHNlZWQiLAoJfQoKCS8vIHdlIGNhbiB1c2UgdGhlIGpzb24uTWFyc2hhbCBmdW5jdGlvbiB0bwoJLy8gZW5jb2RlIHRoZSBwaWdlb24gdmFyaWFibGUgdG8gYSBKU09OIHN0cmluZwoJZGF0YSwgXyA6PSBqc29uLk1hcnNoYWwocGlnZW9uKQoJLy8gZGF0YSBpcyB0aGUgSlNPTiBzdHJpbmcgcmVwcmVzZW50ZWQgYXMgYnl0ZXMKCS8vIHRoZSBzZWNvbmQgcGFyYW1ldGVyIGhlcmUgaXMgdGhlIGVycm9yLCB3aGljaCB3ZQoJLy8gYXJlIGlnbm9yaW5nIGZvciBub3csIGJ1dCB3aGljaCB5b3Ugc2hvdWxkIGlkZWFsbHkgaGFuZGxlCgkvLyBpbiBwcm9kdWN0aW9uIGdyYWRlIGNvZGUKCgkvLyB0byBwcmludCB0aGUgZGF0YSwgd2UgY2FuIHR5cGVjYXN0IGl0IHRvIGEgc3RyaW5nCglmbXQuUHJpbnRsbihzdHJpbmcoZGF0YSkpCn0=",
    "language": "go",
    "args": "run",
    "ext": "go"
}
```

* FailOnError
If true will stop pipeline with an error, if false will let the pipeline continue but the output will show a property success with value false.

```
false
```

## RAW Object

```
{"name":"json-generator-connector","type":"connector","stepName":"Go B64 Code","params":{"json":"{\n    \"b64code\": \"cGFja2FnZSBtYWluCgppbXBvcnQgKAoJImVuY29kaW5nL2pzb24iCgkiZm10IgopCgovLyBUaGUgc2FtZSBqc29uIHRhZ3Mgd2lsbCBiZSB1c2VkIHRvIGVuY29kZSBkYXRhIGludG8gSlNPTgp0eXBlIEJpcmQgc3RydWN0IHsKCVNwZWNpZXMgICAgIHN0cmluZyBganNvbjoiYmlyZFR5cGUiYAoJRGVzY3JpcHRpb24gc3RyaW5nIGBqc29uOiJ3aGF0IGl0IGRvZXMiYAp9CgpmdW5jIG1haW4oKSB7CglwaWdlb24gOj0gJkJpcmR7CgkJU3BlY2llczogICAgICJQaWdlb24iLAoJCURlc2NyaXB0aW9uOiAibGlrZXMgdG8gZWF0IHNlZWQiLAoJfQoKCS8vIHdlIGNhbiB1c2UgdGhlIGpzb24uTWFyc2hhbCBmdW5jdGlvbiB0bwoJLy8gZW5jb2RlIHRoZSBwaWdlb24gdmFyaWFibGUgdG8gYSBKU09OIHN0cmluZwoJZGF0YSwgXyA6PSBqc29uLk1hcnNoYWwocGlnZW9uKQoJLy8gZGF0YSBpcyB0aGUgSlNPTiBzdHJpbmcgcmVwcmVzZW50ZWQgYXMgYnl0ZXMKCS8vIHRoZSBzZWNvbmQgcGFyYW1ldGVyIGhlcmUgaXMgdGhlIGVycm9yLCB3aGljaCB3ZQoJLy8gYXJlIGlnbm9yaW5nIGZvciBub3csIGJ1dCB3aGljaCB5b3Ugc2hvdWxkIGlkZWFsbHkgaGFuZGxlCgkvLyBpbiBwcm9kdWN0aW9uIGdyYWRlIGNvZGUKCgkvLyB0byBwcmludCB0aGUgZGF0YSwgd2UgY2FuIHR5cGVjYXN0IGl0IHRvIGEgc3RyaW5nCglmbXQuUHJpbnRsbihzdHJpbmcoZGF0YSkpCn0=\",\n    \"language\": \"go\",\n    \"args\": \"run\",\n    \"ext\": \"go\"\n}","failOnError":false},"id":"40681e35-71c3-426e-8cca-5af86cb532d8","__documentation__":""}
```