## HomeLab und Workstation

Jeder Systemadministrator hat seinen Spielplatz.

Zum Zeitpunkt des Schreibens verwende ich einen Server mit [Unraid](https://unraid.net/) und 32TB HDD speicher. Für das Netzwerk werden [Unifi](https://www.ui.com/) Switches und Wlan Access Points eingesetzt. Mithilfe von [Tailscale](https://tailscale.com/) kann ich jederzeit auf die, in Docker Containern, laufenden Dienste wie [GitTea](https://gitea.io/en-us/) oder [Syncthing](https://syncthing.net/) zugreifen. Das Monitoring für alle meine Dienste im Intra- sowie Internet wird durch [Uptime Kuma](https://github.com/louislam/uptime-kuma) abgedeckt. Dank Offsite Backup auf eigener Hardware und [AWS S3 Glacier](https://aws.amazon.com/s3/storage-classes/glacier/) wird die [3-2-1 Regel](https://www.veeam.com/blog/321-backup-rule.html) eingehalten. Email Server und öffentlich zugängliches Hosting werden aus Sicherheitsgründen über Internet Dienstleister geregelt.

Für die Entwicklung meiner Privaten Projekte verwende ich meine selbstgebaute Wassergekühlte Workstation.

:::gallery
<a href="img/gallery/homelab-1.webp?h={auto.hash}" onclick="openLightbox(event);"><img alt="Test des Homelab Servers" src="img/gallery/homelab-1_thumb.webp?h={auto.hash}" loading="lazy"></a>
<a href="img/gallery/homelab-2.webp?h={auto.hash}" onclick="openLightbox(event);"><img alt="Workstation" src="img/gallery/homelab-2_thumb.webp?h={auto.hash}" loading="lazy"></a>
:::