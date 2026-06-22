# DTLS-Tamarin-Models
This repo contains Tamarin models for DTLS 1.3 along with proofs for the modeled security properties.

## Models
In the Models folder, the models for the full handshake, PSK handshake, and record layer can be found.
These models can be loaded into Tamarin Prover. From there, the security properties (encoded as lemmas) may be verified. 

## Proofs
In the proofs folder, proofs for all the verified security properties can be found. Note that these proofs cannot be loaded directly into Tamarin prover as this will cause the proofs to malform. They may be read to verify their authenticity or be used to reproduce the same proofs when loading in one of the models.
