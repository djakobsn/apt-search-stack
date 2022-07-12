FROM quay.io/keycloak/keycloak@sha256:b4841a7b8401fd209bfcddf10773cdfa7c7cfde4bf7e87780663226be5587ee2 as builder

#COPY realm.json /opt/keycloak/data/import/realm.json
WORKDIR /opt/keycloak
ENTRYPOINT ["/opt/keycloak/bin/kc.sh", "start", "--proxy", "passthrough", "--import-realm"]