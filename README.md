# telco-411-preview-docs

Pull the latest container from quay.io:

`$ podman pull quay.io/rhn_support_aireilly/telco-411-preview-docs:latest`

Run the container:

`$ podman container run -d -p 5000:80 quay.io/rhn_support_aireilly/telco-411-preview-docs:latest`

The container hosted docs are served at: http://localhost:5000/index.html
