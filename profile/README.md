# ChargerDojo

**Test EV roaming integrations before your partners do.**

[ChargerDojo](https://chargerdojo.com) is the OCPI testing platform for CPOs, eMSPs, payment
terminal providers and roaming hubs. Point it at your endpoint and it plays the other side of the
wire: a strict counterparty that grades every message against the spec, and a controllable one that
misbehaves on purpose, so you find the bugs that would otherwise surface after a billing cycle.

## What you can do

- **Run conformance suites** on OCPI 2.1.1, 2.2, 2.2.1 and 2.3.0, with every check tied to the
  clause of the spec it enforces.
- **Drive timed charging journeys** end to end, with disturbances you control, and load runs of up
  to 500 parallel sessions.
- **Test through roaming hubs**, with Gireve and Plugsurfing Roam profiles, hub identity and relay.
- **Cover the extensions**: Direct Payment, 2.3.0 Payments and Bookings.
- **Put it in your pipeline** with API keys, scheduled runs and a GitHub Action that fails the
  build when an endpoint breaks a rule.
- **Reach an endpoint behind your firewall** with the local connector.
- **Share the evidence**: every exchanged message in a report your partner opens from one link.
- **Ask your coding agent**: a hosted MCP server at `mcp.chargerdojo.com` answers OCPI questions and
  reads your runs from Claude Code, Codex, Cursor or any MCP client.
- **Learn the protocol free** with a guided EV roaming simulator, the module Explorer and the
  Learning Hub.

OCPP testing for CSMS vendors and charger makers is launching soon.

## Open source

- [dojo-connect](https://github.com/chargerdojo/dojo-connect): the local connector. Test an OCPI
  endpoint on your own machine without exposing it to the internet.
- [ocpi-conformance-action](https://github.com/chargerdojo/ocpi-conformance-action): run
  ChargerDojo conformance suites in GitHub Actions and fail the build when an endpoint breaks a
  rule.

## Get started

- Start free on the Sandbox plan: [chargerdojo.com](https://chargerdojo.com)
- Docs and guides: [docs.chargerdojo.com](https://docs.chargerdojo.com)
- Plans and pricing: [sales@chargerdojo.com](mailto:sales@chargerdojo.com)
- Technical help: [support@chargerdojo.com](mailto:support@chargerdojo.com)
