# datasphere_dummy

Test-/Dummy-Kundenrepo zum Nachweis der Multi-Tenant-Faehigkeit des
zentralen Guard/CI-CD-Hub-Repos (siehe `PAGNOS/pagnos-dsp-git-hub`,
Architekturplan Schritt 8). Struktur identisch zu echten Kunden-Repos:
Datasphere-Exportinhalt unter `spaces/<Space>/<Unterordner>/<Datei>`,
Guard-/Deploy-Pruefung laeuft ueber die beiden Dispatch-Stubs in
`.github/workflows/` gegen das zentrale Hub-Repo.
