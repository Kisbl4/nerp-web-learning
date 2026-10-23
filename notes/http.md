C:\Users\Hozyin>curl -I https://example.com
HTTP/1.1 200 OK
Date: Thu, 15 Oct 2026 20:30:40 GMT
Content-Type: text/html; charset=utf-8
Connection: keep-alive
Server: cloudflare
last-modified: Tue, 13 Oct 2026 22:05:48 GMT
allow: GET, HEAD
Accept-Ranges: bytes
Age: 1732
cf-cache-status: HIT
CF-RAY: a4b19540ea61709f-DUS
alt-svc: h3=":443"; ma=86400

C:\Users\Hozyin>curl -I https://github.com
HTTP/1.1 200 OK
Date: Thu, 15 Oct 2026 20:32:42 GMT
Content-Type: text/html; charset=utf-8
content-language: en-US
Vary: X-PJAX, X-PJAX-Container, Turbo-Visit, Turbo-Frame, X-Requested-With, X-GitHub-Client-Version, Accept-Language, Sec-Fetch-Site,Accept-Encoding, Accept, X-Requested-With
ETag: W/"fe2d239e713b76edfa519e7ececcc118"
Cache-Control: max-age=0, private, must-revalidate
Strict-Transport-Security: max-age=31536000; includeSubdomains; preload
X-Frame-Options: deny
X-Content-Type-Options: nosniff
X-XSS-Protection: 0
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Security-Policy: default-src 'none'; base-uri 'self'; child-src github.githubassets.com github.com/assets-cdn/worker/ github.com/assets/ gist.github.com/assets-cdn/worker/; connect-src 'self' uploads.github.com www.githubstatus.com collector.github.com raw.githubusercontent.com api.github.com github-cloud.s3.amazonaws.com github-production-repository-file-5c1aeb.s3.amazonaws.com github-production-upload-manifest-file-7fdce7.s3.amazonaws.com github-production-user-asset-6210df.s3.amazonaws.com *.rel.tunnels.api.visualstudio.com wss://*.rel.tunnels.api.visualstudio.com github.githubassets.com objects-origin.githubusercontent.com copilot-proxy.githubusercontent.com proxy.individual.githubcopilot.com proxy.business.githubcopilot.com proxy.enterprise.githubcopilot.com *.actions.githubusercontent.com wss://*.actions.githubusercontent.com productionresultssa0.blob.core.windows.net productionresultssa1.blob.core.windows.net productionresultssa2.blob.core.windows.net productionresultssa3.blob.core.windows.net productionresultssa4.blob.core.windows.net productionresultssa5.blob.core.windows.net productionresultssa6.blob.core.windows.net productionresultssa7.blob.core.windows.net productionresultssa8.blob.core.windows.net productionresultssa9.blob.core.windows.net productionresultssa10.blob.core.windows.net productionresultssa11.blob.core.windows.net productionresultssa12.blob.core.windows.net productionresultssa13.blob.core.windows.net productionresultssa14.blob.core.windows.net productionresultssa15.blob.core.windows.net productionresultssa16.blob.core.windows.net productionresultssa17.blob.core.windows.net productionresultssa18.blob.core.windows.net productionresultssa19.blob.core.windows.net github-production-repository-image-32fea6.s3.amazonaws.com github-production-release-asset-2e65be.s3.amazonaws.com insights.github.com wss://alive.github.com wss://alive-staging.github.com api.githubcopilot.com api.individual.githubcopilot.com api.business.githubcopilot.com api.enterprise.githubcopilot.com wss://production-copilot-host.webpubsub.azure.com api.github.com/cmc_internal/api/ edge.fullstory.com rs.fullstory.com; font-src github.githubassets.com; form-action 'self' github.com gist.github.com copilot-workspace.githubnext.com objects-origin.githubusercontent.com; frame-ancestors 'none'; frame-src viewscreen.githubusercontent.com notebooks.githubusercontent.com www.youtube-nocookie.com; img-src 'self' data: blob: github.githubassets.com media.githubusercontent.com camo.githubusercontent.com identicons.github.com avatars.githubusercontent.com private-avatars.githubusercontent.com github-cloud.s3.amazonaws.com objects.githubusercontent.com release-assets.githubusercontent.com secured-user-images.githubusercontent.com user-images.githubusercontent.com private-user-images.githubusercontent.com opengraph.githubassets.com repository-images.githubusercontent.com marketplace-screenshots.githubusercontent.com copilotprodattachments.blob.core.windows.net/github-production-copilot-attachments/ github-production-user-asset-6210df.s3.amazonaws.com customer-stories-feed.github.com spotlights-feed.github.com explore-feed.github.com *.googleusercontent.com objects-origin.githubusercontent.com *.githubusercontent.com images.ctfassets.net/8aevphvgewt8/; manifest-src 'self'; media-src github.com user-images.githubusercontent.com secured-user-images.githubusercontent.com private-user-images.githubusercontent.com github-production-user-asset-6210df.s3.amazonaws.com gist.github.com github.githubassets.com assets.ctfassets.net/8aevphvgewt8/ videos.ctfassets.net/8aevphvgewt8/; script-src github.githubassets.com 'sha256-tSjmyPUky1KbRZ0fw9VUil3wFEbeM82rtbJDygGJAXw='; style-src 'unsafe-inline' github.githubassets.com; upgrade-insecure-requests; worker-src github.githubassets.com github.com/assets-cdn/worker/ github.com/assets/ gist.github.com/assets-cdn/worker/
Server: github.com
Accept-Ranges: bytes
Set-Cookie: _gh_sess=UAhviIDmUVSLD9CgEi%2BEOhzx6LZ5Ztm2psm01tg6g0TSTFNSF0p5VZK94TWeErKc6ew4dGaqshJHz6yD3JVvz0gMCj9lpPr4snWlHqUBaRoCZV2PW6sQ6QbhE3qHHfJhfxcuu2sNx3TyJFEZDfxepJ3cuYoBvzJQ6gWZYDaZrtC4wbi1iXYPD3GiFXr1bJsNIFpnQyTM%2Bw0b4Bh90MpfMJxhmY8zLOdG3Iqr1EFdtWMpxxl090MNLiQMfeN8MOtjq8XR%2BdjMNI7MjeTAHhzjFg%3D%3D--OSZxMfWDNWcB7OYI--ZMpczTCiFyqatDW20%2FbLXA%3D%3D; path=/; HttpOnly; secure; SameSite=Lax
Set-Cookie: _octo=GH1.1.98179557.1792096366; expires=Fri, 15 Oct 2027 20:32:46 GMT; domain=.github.com; path=/; secure; SameSite=Lax
Set-Cookie: logged_in=no; expires=Fri, 15 Oct 2027 20:32:46 GMT; domain=.github.com; path=/; HttpOnly; secure; SameSite=Lax
X-GitHub-Request-Id: CD1C:38464:311960E:3F45FBF:6AD1386E
x-github-edge-region: fra

C:\Users\Hozyin>curl -I http://github.com
HTTP/1.1 301 Moved Permanently
Content-Length: 0
Location: https://github.com/