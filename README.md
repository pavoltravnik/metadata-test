# metadata-server-mock-test

Testing HTTP requests by opensource project [newman](https://github.com/postmanlabs/newman).

```bash
npm install -g newman

newman run \
    -d data.json \
    -e environments/PROD.json \
    -g globals.json \
    -n 1 \
    collections/Metadata.json
```