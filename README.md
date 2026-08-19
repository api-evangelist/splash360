# Splash 360 (splash360)

French vendor of point-of-sale and management software for collective catering — company
restaurants, school and institutional canteens. Smart till, ordering kiosks, Wifi Order, Kitchen
Display System, back office, coin handler, and loyalty via YouFid.

**APIs.json:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/splash360/refs/heads/main/apis.yml)

- **Website:** https://splash360.fr

Part of the [API Evangelist](https://apievangelist.com) network.

## No public API surface

Submitted through the apis.io Add-API form on 2026-08-19 and parked by the gate as
`no_consumable_surface`. Listed by hand rather than dropped.

A valid company on a domain it owns gets a listing even with no public API — the low score is the
product, not a reason to withhold the entry. Probed with a browser user-agent on 2026-08-19:
`/api`, `/developers`, `/developpeurs`, `/docs`, `/openapi.json`, `/apis.json` and `/llms.txt` all
return 404, and an invented path returns a genuine 404 too, so the host discriminates and these are
real absences rather than bot protection hiding them.

Worth stating precisely: this is the absence of a *public* interface, not the absence of APIs. A
till, a kiosk and a kitchen display exchanging orders are API-driven by construction. Those
interfaces reach customers through deployment and integration work rather than a public developer
program.
