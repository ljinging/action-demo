# This workflow will build and push a new container image to Alibaba Cloud Container Reigstry (ACR),
# and then will deploy it to Alibaba Cloud Container Service for Kubernetes (ACK), when a release is created.
#
# To use this workflow, you will need to complete the following set-up steps:
#
# 1. Create an ACR repository to store your container images. 
#    You can use ACR EE instance for more security and better performance.
#    For instructions see https://www.alibabacloud.com/help/doc-detail/142168.htm
#
# 2. Create an ACK cluster to run your containerized application.
#    You can use ACK Pro cluster for more security and better performance.
#    For instructions see https://www.alibabacloud.com/help/doc-detail/95108.htm
#
# 3. Add the your AccessKey pair as secrets in the GitHub repository.
#    For instructions on setting up secrets see: https://developer.github.com/actions/managing-workflows/storing-secrets/
#
# 4. Change the values for the AZURE_WEBAPP_NAME, AZURE_WEBAPP_PACKAGE_PATH and NODE_VERSION environment variables  (below).
#
