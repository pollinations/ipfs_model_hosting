# IPFS Model Hosting

An effort to host commonly used deep learning models on the decentralized interplanetary filesystem (IPFS). 

Pain: Large models are often shared by researchers via Google Drive links which have transfer limits and are not reliably online. IPFS provides a great decentralized solution to hosting data which can be downloaded via regular web links.

Pull requests welcome!

Another great source of publicly hosted models is on [The Eye](https://the-eye.eu/public/AI/).

# To upload to IPFS

Via a simple form: https://anarkrypto.github.io/upload-files-to-ipfs-from-browser-panel/public/

Or with your own node:
- Upload the files to any IPFS node. (It should be possible to use IPFS Desktop but syncing with the network can take some time at first)
- Note down the content id and cache it to all public gateways using https://natoboram.gitlab.io/public-gateway-cacher/
- running `ipfs swarm connect /ip4/172.65.0.13/tcp/4009/p2p/QmcfgsJsMtx6qJb74akCw1M24X1zFwgGo11h1cuhwQjtJP` can help in seeding the file faster to the public gateways

To contribute a model, fork this repository, add the model name and hash to the [README.md](README.md) and make a pull request.

# Models

## AdaBins: Depth Estimation using Adaptive Bins (pretrained models)
https://arxiv.org/abs/2011.14141

[Qmd2mMnDLWePKmgfS8m6ntAg4nhV5VkUyAydYBp8cWWeB7/AdaBins_kitti.pt](https://cloudflare-ipfs.com/ipfs/Qmd2mMnDLWePKmgfS8m6ntAg4nhV5VkUyAydYBp8cWWeB7/AdaBins_kitti.pt)
[Qmd2mMnDLWePKmgfS8m6ntAg4nhV5VkUyAydYBp8cWWeB7/AdaBins_nyu.pt](https://cloudflare-ipfs.com/Qmd2mMnDLWePKmgfS8m6ntAg4nhV5VkUyAydYBp8cWWeB7/AdaBins_nyu.pt)

## From https://github.com/justinpinkney/awesome-pretrained-stylegan

## WikiArt 1024

![montage](https://user-images.githubusercontent.com/605492/141532578-29671e5a-ee04-4332-93f9-66fb76a5dc24.jpg)

- **Name**: WikiArt-1024
- **Download URL**: https://cloudflare-ipfs.com/ipfs/QmSC4psV1MYuN2CJ7rfRfQM1GWq8nVpNd5z1XSYnRBLFzg?filename=wikiart-1024-stylegan3-t-17.2Mimg.pkl
- **Author**: Justin Pinkney/LambdaLabs
- **Author URL**: https://www.justinpinkney.com/ https://lambdalabs.com/
- **Dataset**: WikiArt
- **Source URL**: https://lambdalabs.com/blog/stylegan-3/
- **Resolution**: 1024x1024
- **Config**: T
- **Notes**: FID=8.1, trained 17.1 Mimgs, gamma=32, mapping layers=2

## Landscapes 256

![montage](https://user-images.githubusercontent.com/605492/142219592-657e1141-33b4-46ea-b501-8999805d1503.jpg)

- **Name**: LHQ-256
- **Download URL**: https://cloudflare-ipfs.com/ipfs/QmeQytEU5jjkfKSceezHCQ6Ys7ovSYVJCidbpTfzmUHpXJ?filename=lhq-256-stylegan3-t-25Mimg.pkl
- **Author**: Justin Pinkney/LambdaLabs
- **Author URL**: https://www.justinpinkney.com/ https://lambdalabs.com/
- **Dataset**: [LHQ](https://github.com/universome/alis/blob/master/lhq.md)
- **Source URL**: https://twitter.com/Buntworthy/status/1460980442409185287?s=20
- **Resolution**: 256x256
- **Config**: T
- **Notes**: FID=2.31, trained 25 Mimgs, gamma=2, mapping layers=2
