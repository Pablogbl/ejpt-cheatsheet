# ejpt-cheatsheet

Cheatsheet interactiva de pentesting en un solo fichero HTML. Pensada para tener a mano durante una máquina o el examen eJPT: pones la IP objetivo una vez y se sustituye en todos los comandos, buscas o filtras por fase, y copias al clic.

**Web:** https://pablogbl.github.io/ejpt-cheatsheet/

## Dos vistas

**⌘ Comandos** — más de 160 comandos organizados por las fases de un pentest, con buscador, filtros por fase, IP dinámica y copiado al clic.

**▤ Guías** — 17 guías paso a paso de "qué hacer en cada situación", encadenadas entre sí: cada una termina indicando hacia dónde seguir (web → conseguir shell → escalar → pivotar).

## Comandos incluidos

- Descubrimiento de red y escaneo de puertos (nmap)
- Enumeración por servicio: web, WordPress, SMB, FTP, DNS, bases de datos, RDP, LDAP, NFS, SMTP, SNMP
- Ataques de red / MITM: captura de hashes con Responder (LLMNR/NBT-NS)
- Web ofensiva: SQLi, sqlmap, LFI, webshells
- Búsqueda de exploits y fuerza bruta
- Cracking de hashes
- Esteganografía y forense de ficheros
- Metasploit y generación de payloads con msfvenom
- Reverse/bind shells y estabilización de TTY
- Transferencia de archivos (Linux y Windows)
- Post-explotación, pivoting (autoroute + proxychains) y escalada de privilegios (Linux y Windows)

## Guías paso a paso

Metodología general, cómo enfocar el examen, y el flujo concreto ante cada situación: encontrar una web, SMB/FTP, SSH, MySQL/MSSQL, WordPress, una máquina Windows, tener una shell, escalar privilegios, pivotar a la red interna, pasar archivos, explotar parámetros web, recursos externos y qué hacer cuando te atascas.

## Características

- **Dos vistas** conmutables: comandos y guías.
- **Dos IPs dinámicas** — la del objetivo y la de tu Kali (atacante); cada comando usa la que le corresponde.
- **Buscador** en tiempo real y **filtros por fase** plegables.
- **Copiar al clic** con un botón en cada comando.
- **Guías encadenadas** — cada una enlaza a la siguiente fase.
- **Recursos externos** enlazados (GTFOBins, LOLBAS, revshells, HackTricks, Wappalyzer, CyberChef…).
- **Sin dependencias** — un único `index.html`, funciona sin conexión abriéndolo en el navegador.

## Uso

Ábrela en la web de arriba, o descarga el `index.html` y ábrelo directamente en el navegador (móvil o PC).

---

⚠️ Material educativo. Pensado para pentesting autorizado y entornos controlados.
