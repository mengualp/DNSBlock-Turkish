<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  Turkish Blocklist
  <link rel="stylesheet" href="https://github.githubassets.com/assets/github-dcaf0f44dbb1.css">
</head>
<body>
  <div class="readme">
    <article>
      <p>
        <a href="https://avatars.githubusercontent.com/u/16763696?v=4" target="_blank">
          <img src="https://avatars.githubusercontent.com/u/16763696?v=4" alt="Cover" style="max-width:100%;">
        </a>
      </p>
      <div align="center">
        <img src="https://img.shields.io/badge/Updated-Nov 11, 2022-green.svg?style=for-the-badge">
        <img src="https://img.shields.io/badge/Status-Stable-blue.svg?style=for-the-badge">
        <img src="https://img.shields.io/badge/License-MPL 2.0-orange.svg?style=for-the-badge">
      </div>
      <table>
        <thead>
          <tr>
            <th>İstemci</th>
            <th>DNS filtresi</th>
            <th>Gizlilik filtresi</th>
            <th>URL izleme filtresi</th>
            <th>İzin verilenler filtresi</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>uBlock - AdGuard</td>
            <td><a href="https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/adblock.txt">RAW</a></td>
            <td><a href="https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/adb-privacy.txt">RAW</a></td>
            <td><a href="https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/adb-urltracking.txt">RAW</a><br>"güvenilir filtre olarak işaretleyin"</td>
            <td><a href="https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Whitelist/adb-whitelist.txt">RAW</a></td>
          </tr>
          <tr><td>Pi-hole</td><td><a href="https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/domains.txt">RAW</a></td><td>-</td><td>-</td><td>-</td></tr>
          <tr><td>AdAway</td><td><a href="https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/hosts.txt">RAW</a></td><td>-</td><td>-</td><td>-</td></tr>
          <tr><td>Unbound</td><td><a href="https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/unbound.conf">RAW</a></td><td>-</td><td>-</td><td>-</td></tr>
          <tr><td>dnsmasq</td><td><a href="https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/dnsmasq.conf">RAW</a></td><td>-</td><td>-</td><td>-</td></tr>
          <tr><td>RPZ</td><td><a href="https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/rpz.txt">RAW</a></td><td>-</td><td>-</td><td>-</td></tr>
          <tr><td>Windows Hosts</td><td><a href="https://raw.githubusercontent.com/saurane/Turkish-Blocklist/master/Blocklist/hosts.win">RAW</a></td><td>-</td><td>-</td><td>-</td></tr>
        </tbody>
      </table>
      <h2>Filtre açıklaması</h2>
      <p><strong>DNS Filtresi:</strong> Alan adı tabanlı engeller. <br><strong>Gizlilik Filtresi:</strong> Dosya yoluna göre engelleme. <br><strong>URL İzleme Filtresi:</strong> İzleme parametrelerini kaldırır. <br><strong>İzin verilenler filtresi:</strong> Uyum problemlerini önlemeye yönelik istisnalar.</p>

      <h2>Amaç</h2>
      <p><strong>DNS filtresi:</strong> Yerli reklam ve analiz adreslerini engeller. %99 Türk kaynaklı. <br><strong>Gizlilik filtresi:</strong> Alan adları içindeki izleyicileri hedefler.</p>

      <h2>Tespit ve araştırma yöntemleri</h2>
      <p>AdGuard, NextDNS, URL Scan gibi araçlar kullanıldı.</p>

      <h2>Sorunlar ve İstekler</h2>
      <p>Her türlü destek ve geri bildirim için <a href="https://github.com/saurane/Turkish-Blocklist/issues">GitHub Issues</a> sayfasını kullanabilirsiniz.</p>
    </article>
  </div>
</body>
</html>
