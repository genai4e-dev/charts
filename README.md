# Genai4E Helm charts

The Helm chart repository for [Genai4E](https://genai4e.com), served at **https://charts.genai4e.com**.

```bash
helm repo add genai4e https://charts.genai4e.com
helm repo update
helm install genai4e genai4e/genai4e -n genai4e --create-namespace \
  --set hostname=ai.example.com --set adminEmail=you@example.com --set-file license=./license.lic
```

The same chart is also published as an OCI artifact: `oci://ghcr.io/genai4e-dev/charts/genai4e`.
Using Genai4E needs a license file: get a free one at [genai4e.com/trial](https://genai4e.com/trial).
Quickstart, examples and docs: [github.com/genai4e-dev/genai4e](https://github.com/genai4e-dev/genai4e).

This repository is updated by Genai4E's release workflow on every release; don't edit it by hand.
