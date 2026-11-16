# ChargerDojo

**Test your OCPI endpoint before your first partner does.**

[ChargerDojo](https://chargerdojo.com) is for engineering teams with their own OCPI endpoint and
a first roaming partner or hub about to connect. Run checks against your endpoint, inspect the
recorded exchanges and send your partner the report.

## What you can do today

- Run conformance suites on OCPI 2.1.1, 2.2.1 and 2.3.0. Read the recorded exchanges and any cited spec clauses.
- Run conformance suites against a private endpoint through the local connector, from Integrate.
- Run timed charging journeys. Test remote start and stop against a CPO, or rehearse faults
  against an eMSP. Journeys need a reachable address or tunnel.
- Test Direct Payment, Payments and Bookings on their supported versions, or hub relay, on Automate.
- Run suites from CI with API keys on Integrate; schedule runs on Automate.
- Share a report your partner can open without an account, with recorded evidence behind the verdicts.
- Explore OCPI free through the simulator, module Explorer and Learning Hub. Ask OCPI questions
  through the hosted MCP server without a key.

## Public repositories

- [dojo-connect](https://github.com/chargerdojo/dojo-connect): released local-connector binaries;
  source is not published in this repository.
- [ocpi-conformance-action](https://github.com/chargerdojo/ocpi-conformance-action): MIT-licensed
  GitHub Action that runs suites on ChargerDojo and fails the build on a failed required check.
  Needs a paid API key.

## What is coming

OCPP testing is launching soon in the same product: charging station management systems (CSMS) on 1.6J
first, then 2.0.1, with charger testing later. Longer term, we plan to test one charge through
OCPP and OCPI, from charger to CSMS to roaming partner.

Not built your endpoint yet? An OCPI library is in early access. It is not released yet; tell us
what you need from it.

We plan to work with the EVRoaming Foundation to get ChargerDojo certified, so the runs you do here line up
with the certification you go for next. ChargerDojo issues no certificate.

## Start testing

- [Start free on Sandbox](https://chargerdojo.com): test our endpoints without a card. Your own
  endpoint needs Integrate or above.
- [Read the docs](https://docs.chargerdojo.com).
- Custom plan: [Talk to us](mailto:sales@chargerdojo.com).
- Technical help: [support@chargerdojo.com](mailto:support@chargerdojo.com).
