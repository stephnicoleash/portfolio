# portfolio

## usage instructions in GitHub CodeSpaces
1. rm -rf public/
2. hugo mod tidy
3. hugo mod npm pack
4. npm install
5. hugo server -D --appendPort=false --baseURL https://$CODESPACE_NAME-1313.$GITHUB_CODESPACES_PORT_FORWARDING_DOMAIN