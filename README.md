# ipfs_model_hosting
An effort to host commonly used deep learning models on the decentralized interplanetary filesystem (IPFS). 

Pain: Large models are often shared by researchers via Google Drive links which have transfer limits and are not reliably online. IPFS provides a great decentralized solution to hosting data which can be downloaded via regular web links.

Pull requests welcome!

# To upload to IPFS

Via a simple form: https://anarkrypto.github.io/upload-files-to-ipfs-from-browser-panel/public/

Or with your own node:
- Upload the files to any IPFS node. (It should be possible to use IPFS Desktop but syncing with the network can take some time at first)
- Note down the content id and cache it to all public gateways using https://natoboram.gitlab.io/public-gateway-cacher/
- running `ipfs swarm connect /ip4/172.65.0.13/tcp/4009/p2p/QmcfgsJsMtx6qJb74akCw1M24X1zFwgGo11h1cuhwQjtJP` can help in seeding the file faster to the public gateways

# Models

## AdaBins: Depth Estimation using Adaptive Bins (pretrained models)
https://arxiv.org/abs/2011.14141

[Qmd2mMnDLWePKmgfS8m6ntAg4nhV5VkUyAydYBp8cWWeB7/AdaBins_kitti.pt](https://ipfs.io/ipfs/Qmd2mMnDLWePKmgfS8m6ntAg4nhV5VkUyAydYBp8cWWeB7/AdaBins_kitti.pt)
[Qmd2mMnDLWePKmgfS8m6ntAg4nhV5VkUyAydYBp8cWWeB7/AdaBins_nyu.pt](https://ipfs.io/ipfs/Qmd2mMnDLWePKmgfS8m6ntAg4nhV5VkUyAydYBp8cWWeB7/AdaBins_nyu.pt)

