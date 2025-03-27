---
title: Swagger CDN
layout: swagger
---

<div id="pet-store-api"></div>

<script>
window.onload = function() {
  SwaggerUIBundle({
    url: '/api-docs/pet-store-api.yaml',
    dom_id: '#pet-store-api',
    presets: [
      SwaggerUIBundle.presets.apis,
      SwaggerUIStandalonePreset
    ],
    layout: "BaseLayout",
  });
};
</script>