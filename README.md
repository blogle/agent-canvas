# Patched Agent Canvas

OpenHands Agent Canvas v1.16.0 with one UI-only patch exposing the upstream
manual `kind=cloud` backend form for self-hosted sandbox-server deployments.

The patch changes only `backend-form-modal.tsx` and its focused component test.
It leaves Cloud OAuth, local Agent Server behavior, backend storage, and all
backend semantics unchanged.

The published image is built from the upstream `OpenHands/OpenHands` tag
`v1.16.0` and is intended for the `nandstorm` deployment.
