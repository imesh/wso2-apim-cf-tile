# Cloud Foundry Tile for WSO2 API Manager

This repository includes a Cloud Foundry Tile for deploying WSO2 API Manager 2.1.0 on BOSH via Pivotal Ops Manager. 

## Quick Start

1. Clone WSO2 API Manager BOSH release repository and export BOSH release:

   ```
   git clone https://github.com/imesh/wso2-apim-bosh-release.git
   cd wso2-apim-bosh-release
   ./export.sh
   ```
2. Copy WSO2 API Manager BOSH release tar.gz file to the root folder of this tile project.

3. Build the tile using the below command:
   
   ```
   tile build --cache cache/
   ```

4. Upload the product/wso2apim-tile-<versiom>.pivotal file to Pivotal Ops Manager and execute a deployment.
