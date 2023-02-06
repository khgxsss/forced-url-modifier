# forced_url
for URL forced FULL encoding &amp; decoding <br/><br/>
by dh kim

## usage

<pre><code>
from forced_url_modifier import URL_Modifier

um = URL_Modifier()

payload = '<script>alert("XSS")</script>'
encoded_payload = um.forced_url_encoding(payload)
print("Encoded payload: ", encoded_payload)


payload = '%3Cscript%3Ealert%28%22XSS%22%29%3C%2Fscript%3E'
decoded_payload = um.forced_url_decoding(payload)
print("Decoded payload: ", decoded_payload)
</code></pre>


