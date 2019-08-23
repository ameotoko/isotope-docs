# Verknüpfte Kategorien

`Verknüpfte Kategorien` werden ausschliesslich im Zusammenhang mit dem Modul <docrobot_route name="related-products">Ähnliche Produkte</docrobot_route> verwendet.

Sie bildet die Basis für die von vielen Webshops bekannte Funktion für Dinge wie

* "Kunden die dieses Produkt gekauft haben, kauften auch"
* Zubehör zu diesem Produkt
* etc.

Eine `verknüpfte Kategorie` ist aber nicht für jedes Produkt immer gleich.
Nehmen wir als Beispiel die "Zubehör"-Funktion. Für Produkt A ist das Zubehör die Produkte X und Y, aber für Produkt B sind es Produkte K und L.

Deshalb wird die Zuordnung für die Kategorien im Produkt selbst vorgenommen.
Sobald du **mindestens eine** `verknüpfte Kategorie` angelegt hast, kannst du bei den <docrobot_route name="product-management">Produkten selbst</docrobot_route>, die Verknüpfungen vornehmen.

## Vorgehen beim Einrichten von ähnlichen Produkten

<ol>
<li>Isotope eCommerce > Shop-Konfiguration > <docrobot_route name="related-categories">Verknüpfte Kategorien</docrobot_route><br><code>Neue Kategorie</code> mit dem Namen <code>Related</code> anlegen.<br><docrobot_image path="backend-configuration/store-configuration/products/related-categories/kategorie_anlegen.png" alt="Neue Kategorie anlegen"></li>
<li>Isotope eCommerce > <docrobot_route name="product-management">Produkte</docrobot_route><br>Zuerst musst du IDs der ähnlichen Produkte herausfinden, fahre dafür über das blaue Icon (<docrobot_image path="images/show.gif" alt="Show-Icon">). Klicke auf das Sitemap-Icon (<docrobot_image path="images/sitemap.png" alt="Sitemap-Icon">). Danach auf <code>Kategorie hinzufügen</code>, wähle die Kategorie <code>Related</code> aus und füge die Produkte-IDs unter <code>Produkte</code> ein.<br>
<docrobot_image path="backend-configuration/store-configuration/products/related-categories/kategorie_hinzufuegen.png" alt="Produkte-IDs hinzufügen"></li>
<li>Module > <docrobot_route name="related-products">Ähnliche Produkte</docrobot_route><br>Modul anlegen und unter Modul-Konfiguration <code>Related</code> auswählen.<br>
<docrobot_image path="backend-configuration/store-configuration/products/related-categories/modul_anlegen.png" alt="Modul Ähnliche Produkte anlegen">
</li>
<li>Inhalte > Artikel<br>
Jetzt das angelegte Modul im Artikel mit <docrobot_route name="product-list">Produktliste</docrobot_route> und <docrobot_route name="product-reader">Produktleser</docrobot_route> platzieren.<br>
<docrobot_image path="backend-configuration/store-configuration/products/related-categories/angelegtes_modul.png" alt="Angelegtes Modul platzieren"></li>
</ol>