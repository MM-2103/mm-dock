# --------------------------------------------------------------------------
# Image Setup
# --------------------------------------------------------------------------

FROM caddy:2-alpine

LABEL maintainer="Cerberos <development@cerberos.dev>"

# --------------------------------------------------------------------------
# Copy Caddyfile configuration
# --------------------------------------------------------------------------

COPY Caddyfile /etc/caddy/Caddyfile

# Caddy runs as non-root user by default (good for rootless Podman)
# No additional setup needed - Caddy handles SSL automatically!
