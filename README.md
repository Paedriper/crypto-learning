# crypto-learning
## Introduction
## Getting Started  
## Features
## Installation
## Usage
## Examples
## Contributing
## License
## FAQ
## Roadmap
chore: initial commit – scaffold Rust workspace and cargo manifest
feat(core): implement basic wallet reputation scoring algorithm
docs: add architecture overview in README with sequence diagram
feat(api): expose /scores endpoint with JWT auth middleware
test: add unit tests for score normalization edge-cases
fix(core): correct overflow bug when staking weight > u128::MAX/2
