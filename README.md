node-express-monitoring

Build the image

```bash
docker build monitoring .
```

Run the container based on the image

```bash
docker run -p9090:9090 monitoring
```