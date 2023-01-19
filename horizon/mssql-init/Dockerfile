# escape=`
ARG BASE_IMAGE
ARG HORIZON_INTEGRATION_ASSET_IMAGE
FROM ${HORIZON_INTEGRATION_ASSET_IMAGE} as horizon_integration
FROM ${BASE_IMAGE} AS cm
COPY --from=horizon_integration C:\module\db C:\resources\hrz