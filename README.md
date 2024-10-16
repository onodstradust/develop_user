#  **yarnova**

**CLI for publishing versioned data bundles to S3 / GCS.**

---

### install

```bash
pip install yarnova
```

### usage

```bash
yarnova push ./dataset --bucket my-data
```

### supports

* AWS S3
* Google Cloud Storage
* Azure Blob (coming soon)

### config

```yaml
bucket: analytics-data
versioning: true
manifest: manifest.json
```

### logs

```
✓ Uploaded 120 files
✓ Created version tag v1.3.0
```

Apache-2.0 © [yarnova.io](https://yarnova.io)

# PR Merge: 2025-10-17 - fix/merge-5216

# PR Update: 2025-10-17 - fix/update-8079
