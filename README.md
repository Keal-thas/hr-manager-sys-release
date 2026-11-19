# HR Manager Release

Password-protected snapshots of a private HR management system.

## Downloads

- `hr-manager-sys-code-v1.0.1.zip`: source code, React frontend, built static assets, docs, and the DOCX conversion tooling.
- `hr-manager-sys-spec-v1.0.1.zip`: converted requirements Markdown, sections, images, and Excel attachments.

Older `v1.0.0` assets remain available under Releases.

## Password

The archive password is provided separately by the project owner. It is not stored in this repository.

## SHA256

```text
76d83b87c0b24d93bfb0d56c61bd73584a5cf9d83544ade7a06f0ec8df0cd6d3  hr-manager-sys-code-v1.0.1.zip
c8296e24697f4190a63d0ae3ad42615f6377c63cdcfc125c7e1d86e96a49d953  hr-manager-sys-spec-v1.0.1.zip
```

## Source

The source repository is private. This release repository is maintained manually.

## Extract

The archives use AES-256. Use 7-Zip or WinRAR.

## Run the code archive

```bash
cd hr-manager-sys
mvn spring-boot:run
```

Default accounts:

```text
10001 / Admin1234
10002 / Hr123456
10003 / Emp123456
```

The default development database is H2. See `README.md` and `docs/` inside the archive.
