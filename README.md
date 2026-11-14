Valxel static site
Upload the CONTENTS of this folder to an Amazon S3 bucket (index.html at the bucket root, assets/ next to it).

S3 static website hosting:
1. Create a bucket.
2. Upload index.html, README.txt if you want, and the assets folder.
3. Properties → Static website hosting → Enable.
4. Index document: index.html
5. Block public access off, then add a bucket policy that allows s3:GetObject for public read.
   Or keep the bucket private and put CloudFront in front of it.

The briefing form does not email anyone. It only confirms on the page.
