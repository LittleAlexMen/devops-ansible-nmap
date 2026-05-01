# Ansible playbook для сканирования портов через nmap

## Содержимое
- `playbook_nmap.yml` – сканирует цели из файла targets.txt (цикл).
- `playbook_nmap_copy.yml` – копирует targets.txt на удалённый хост и использует `-iL`.
- `targets.txt` – список доменов/IP для сканирования.

