FROM mcr.microsoft.com/devcontainers/javascript-node:1-20-bookworm

# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>

# [Optional] Uncomment if you want to install an additional version of node using nvm
# ARG EXTRA_NODE_VERSION=10
# RUN su node -c "source /usr/local/share/nvm/nvm.sh && nvm install ${EXTRA_NODE_VERSION}"

# [Optional] Uncomment if you want to install more global node modules
# RUN su node -c "npm install -g <your-package-list-here>"

# enable Corepack (https://nodejs.org/docs/latest-v18.x/api/corepack.html)
# Corepack will know to use a modern version of Yarn because of the
# packageManager field in the root package.json
# solves issue: https://community.redwoodjs.com/t/blog-tutorial-auth-setup-and-storybook-yarn-workspace-errors/5860/2
RUN corepack enable
