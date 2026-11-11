# TicketsData API

**Real-time event and ticketing data API.** Live listings, prices, fees and seat-level inventory from ten primary and secondary ticket marketplaces, delivered as clean JSON through one REST API.

[Website](https://ticketsdata.com) · [API Docs](https://ticketsdata.com/docs) · [Pricing](https://ticketsdata.com/pricing) · [Marketplaces](https://ticketsdata.com/marketplaces) · [Postman](https://www.postman.com/ticketsdata)

## What TicketsData API does

- **Live listings for any event.** Sections, rows, quantities, list prices, fees and all-in prices, fetched in real time with no cache.
- **Event discovery.** Every upcoming event for a performer, venue or organizer in one call.
- **Cross-market reports.** Match one event across marketplaces and compare prices, inventory and section-level spreads.
- **Event catalogs.** Full and incremental exports of stored events with location, date and on-sale filters.
- **MCP server.** Connect Claude, Cursor and other AI assistants to live ticket data.

## Who uses it

Ticket brokers, analytics teams, developers building price comparison and alert apps, and AI agents that need real-time ticket market data.

## Repositories

| Repository | Description |
|---|---|
| [ticketmaster-api-alternative](https://github.com/ticketsdata/ticketmaster-api-alternative) | Unofficial Ticketmaster API alternative: quick start, endpoints and code examples in Python, Node.js and cURL |
| [ticketsdata-mcp](https://github.com/ticketsdata/ticketsdata-mcp) | MCP server for live ticket listings, prices and fees |

## Get started

Create a free account at [ticketsdata.com](https://ticketsdata.com). The trial needs no credit card and includes API credits and match reports to test the API.

```bash
curl -G "https://ticketsdata.com/fetch" \
  --data-urlencode "username=$TD_USERNAME" \
  --data-urlencode "password=$TD_PASSWORD" \
  --data-urlencode "platform=ticketmaster" \
  --data-urlencode "event_url=<EVENT_URL>"
```

## Contact

- Email: info@ticketsdata.com
- X: [@ticketsdata_com](https://x.com/ticketsdata_com)
- LinkedIn: [company/ticketsdata](https://www.linkedin.com/company/ticketsdata)
- YouTube: [ticketsdata](https://youtube.com/ticketsdata)

---

TicketsData™ is a trade mark of TicketsData Ltd, registered in England and Wales (company no. 17150266). [ticketsdata.com](https://ticketsdata.com) is the only official TicketsData website. TicketsData is not affiliated with any ticket marketplace.
