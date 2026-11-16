# HR Manager Release

Password-protected snapshots of a private HR management system.

## Downloads

- `hr-manager-sys-code-v1.0.0.zip`: source code, React frontend, built static assets, docs, and the DOCX conversion tooling.
- `hr-manager-sys-spec-v1.0.0.zip`: converted requirements Markdown, sections, images, and Excel attachments.

## Password

The archive password is provided separately by the project owner. It is not stored in this repository.

## SHA256

```text
a7a78c47e4b8552a2a462392ff50f12593378c58bb71165a13cbb5cf7bd952b5  hr-manager-sys-code-v1.0.0.zip
5a9540454d422a3318b1e805f53c7feae8b572a761516c596a7e86cb0b414ba9  hr-manager-sys-spec-v1.0.0.zip
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
