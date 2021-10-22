
FROM rust:1.56.0-slim-bullseye

COPY ./polkadot-musl-builder.sh /polkadot-musl-builder.sh
RUN chmod +x /polkadot-musl-builder.sh

# Run the script to generate the Polkadot binary
RUN /polkadot-musl-builder.sh build

