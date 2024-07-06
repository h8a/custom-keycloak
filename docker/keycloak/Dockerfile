FROM quay.io/keycloak/keycloak:25.0

ENV KC_DB=postgres
RUN /opt/keycloak/bin/kc.sh build --db=postgres

ENTRYPOINT ["/opt/keycloak/bin/kc.sh", "start", "--optimized"]
