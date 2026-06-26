# BirdLife Tools

Open-source conservation technology for bird and wildlife organizations worldwide.

## Mission

Free tools that solve real operational problems for frontline conservation organizations — so they spend time in the field, not on administration.

Guided by *Sympatheia* — awareness of the interconnectedness of all parts of nature.

## Foundation

All BirdLife tools share a common data language and ID system — ensuring interoperability across the ecosystem.

| Component | Description | Status |
|-----------|-------------|--------|
| [birdlife-schema](https://github.com/birdlife-tools/birdlife-schema) | Data contract schemas (Apache Avro) + validation CLI | [![v0.3.6](https://img.shields.io/badge/released-v0.3.6-green)](https://github.com/birdlife-tools/birdlife-schema/releases/tag/v0.3.6) |
| [Resolution API](https://birdlife.tech/docs) | Deterministic ID generation for taxa and locations | [![live](https://img.shields.io/badge/status-live-brightgreen)](https://birdlife.tech/docs) |

**What it provides:**
- **Canonical shapes** for Taxon, Observation, Location, Observer, Protocol, Evidence
- **Darwin Core alignment** — compatible with GBIF and global biodiversity standards
- **Deterministic IDs** — same scientific name → same UUID, everywhere, always
- **Location deduplication** — coordinates within ~11m resolve to the same ID
- **Schema validation** — tools declare and verify compatibility

[![Matrix](https://img.shields.io/badge/Matrix-%23birdlife--schema-black?logo=matrix)](https://matrix.to/#/#birdlife-schema:matrix.org)

## Tools

### Data & Citizen Science
| Repository | Description | Status |
|------------|-------------|--------|
| [ebird-iucn-synthesizer](https://github.com/birdlife-tools/ebird-iucn-synthesizer) | Synthesize eBird sightings with IUCN Red List threat data | 🚧 Planning |
| [bird-collision-reporter](https://github.com/birdlife-tools/bird-collision-reporter) | PWA for reporting bird-glass collisions with GPS | 🚧 Planning |
| [volunteer-hotspot-finder](https://github.com/birdlife-tools/volunteer-hotspot-finder) | Find data gaps and propose survey missions | 🚧 Planning |

### Monitoring & Early Warning
| Repository | Description | Status |
|------------|-------------|--------|
| [audiomoth-pipeline](https://github.com/birdlife-tools/audiomoth-pipeline) | Process AudioMoth recordings through BirdNET | 🚧 Planning |
| [satellite-habitat-watch](https://github.com/birdlife-tools/satellite-habitat-watch) | Sentinel-2 alerts for habitat destruction | 🚧 Planning |
| [radar-migration-tracker](https://github.com/birdlife-tools/radar-migration-tracker) | Extract bird migration from weather radar | 🚧 Planning |

### Science & Administration
| Repository | Description | Status |
|------------|-------------|--------|
| [eco-lawyer](https://github.com/birdlife-tools/eco-lawyer) | Generate legal complaints from field reports | 🚧 Planning |
| [edna-barcoding](https://github.com/birdlife-tools/edna-barcoding) | eDNA sequence analysis for species detection | 🚧 Planning |
| [population-viability](https://github.com/birdlife-tools/population-viability) | Monte Carlo population survival simulator | 🚧 Planning |

## Community

Join our Matrix space to discuss, ask questions, and collaborate:

[![Matrix](https://img.shields.io/badge/Matrix-Join%20Space-black?logo=matrix)](https://matrix.to/#/#birdlife-tools:matrix.org)

Each tool has its own channel for focused discussion.

## Contributing

All tools are MIT licensed. Contributions welcome — see individual repos for setup guides.

## Localization

Tools support international use:
- English as default language
- Country-specific data sources via configuration
- Region-specific setup guides in `docs/localization/`

---

*This is an independent open-source community project and is not affiliated with or endorsed by BirdLife International.*
