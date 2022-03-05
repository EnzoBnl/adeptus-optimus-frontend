# Adeptus Optimus Frontend

Go to deploy: [![Actions Status](https://github.com/bonnal-enzo/adeptus-optimus-frontend/workflows/deploy/badge.svg?branch=prod)](https://adeptus-optimus.web.app/)
Go to preview: [![Actions Status](https://github.com/bonnal-enzo/adeptus-optimus-frontend/workflows/deploy-preview/badge.svg?branch=prod)](https://github.com/bonnal-enzo/adeptus-optimus-frontend/actions)

# Init deployment on Firebase
```
sudo apt-get autoremove 
curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash - 
sudo apt-get install -y nodejs
npm install -g firebase-tools
firebase login
firebase init
firebase deploy
```

# Test locally
In root (avoid CORS issues locally):

`chromium-browser --disable-web-security --user-data-dir ./public/index.html`

Dev query string: `id=admin&token=U2FsdGVkX197wfW/IY0sqa/Ckju8AeU3pRLPSra1aCxZeAHrWePPDPJlYTy5bwdU`
