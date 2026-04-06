
*Low-latency content delivery with Cloud CDN*

Content delivery network

Intended to serve content to users with low latency, by having cached endpoints around the world

It stores frequently accessed content closer to users

Content is stored in a multi-region Cloud Storage bucket

*Example*

User requests a file

CDN checks if the file is already cached at the nearest endpoint

If cached, delivered, instead of the central storage bucket

If not, gets from central storage bucket, then cache it in the endpoint

*Good for*

1) Global users
2) High traffic volumes
3) Minimize latency and egress costs




