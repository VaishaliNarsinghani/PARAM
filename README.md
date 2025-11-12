## Param — Key Qualities (Ready to Paste)

- **Role-based & traceable**
  - Six profiles: Initiator, Coordinator, Field Engineer, Report Drafter, Technical Manager, CSO
  - Fine-grained access control, explicit case states, full audit trail

- **End-to-end valuation workflow**
  - Initiate → Assign → Visit → Draft → Review → Deliver
  - Reference-ID lifecycle with flags/SLA timers and return-for-rework gates

- **Field-ops first**
  - Android FE integration (online/offline), buffered GPS tracks, geotagged photos
  - Route overlays, distance calculations, visit validation

- **High-throughput media handling**
  - Path-based storage (fast DB, low bloat), up to 50 images per case
  - EXIF/orientation handling, curated **final** image sets for reports

- **Report production that scales**
  - Data-driven templates, preview → approve → finalize
  - PDF bundling and bank-specific formatting readiness

- **Operations visibility**
  - Live engineer map with clustering & route thinning
  - Branch filters, powerful search, pagination, quick triage views

- **Reliable data layer**
  - MySQL/MariaDB (`project_db`) with prepared statements & indexes
  - Clear table boundaries (e.g., `uploaded_images`, `final_upload_photo`, `engineer_live`, `gps_track_log`)

- **Performance & resilience**
  - Low-bandwidth friendly sync, defer/retry for uploads
  - Fast reads via path storage; minimal payloads for dashboards

- **Security & compliance basics**
  - Server-side validation, minimal PII in logs, role-scoped endpoints
  - Separate public URL base vs absolute disk paths to avoid leakage

- **Deployment-ready**
  - LAMP stack (e.g., AWS Lightsail Bitnami), HTTPS via Let’s Encrypt
  - Env-based config; works behind reverse proxies/CDN

- **Extensible architecture**
  - Modular controllers/views, pluggable report templates
  - Hooks for CRM/ERP integration, SLA/export reports

- **Maintainable & ops-friendly**
  - Clear error surfaces, audit logs, rollback-safe states
  - Consistent naming, reference-ID strategy, predictable folders

- **GIS-aware**
  - Leaflet maps, overlays, branch/area views
  - Geo-validation for visits and travel sanity checks

- **UX that reduces rework**
  - Preview/approve checkpoints, explicit flags, guided forms
  - Instant feedback on uploads and draft status

- **Roadmap-ready**
  - Webhooks, anomaly detection (GPS/photo), bulk SLA analytics
  - Multi-bank report packs & templated exports
