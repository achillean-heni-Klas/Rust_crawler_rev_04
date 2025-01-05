
#  **datapack**

**CLI for versioned data publishing to S3 / GCS.**

---

### install

```bash
pip install datapack
```

### usage

```bash
datapack push ./dataset --bucket my-data
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

Apache-2.0 ©
