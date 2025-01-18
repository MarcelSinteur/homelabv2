# Marcel Sinteur homelab
This repository will serve as my personal homelab. It serves two purposes:
- Convenience, since automating as much as possible is what I love to do.
- Learning. There is no better way for me to learn, than to just do. Why not make something useful in the process?

My homelab utilizes FluxCD and its best practices.

If there's anything you're seeing that could be improved, please don't hesitate to let me know.

# Hardware
Currently I am running a one node cluster, which I obviously intend to expand in the near future. 

I am running this on an HP ELITEDESK 800 G2 SFF with the following specs:
- CPU: Intel Core i5 6500 3.2GHz
- RAM: 16GB DDR4
- Storage: 500GB HDD

I also have a Synology NAS that serves as my main storage. 

# Secrets
I use ExternalSecrets. To maximize security, I have decided to use Azure KeyVault as my secrets storage. This way, I do not have to expose any secrets in my source code and my secrets are very easy to add, modify or delete.

If you want to know how I've achieved this, the best guide I've found is: https://external-secrets.io/v0.4.3/provider-azure-key-vault/

# References
To create my homelab, there were several invaluable resources such as:
- FluxCD: https://fluxcd.io/flux/guides, this describes FluxCD best practices.
- Mischa van den Burg: https://github.com/mischavandenburg/homelab, amazing DevOps engineer and his repo has proved to be an incredible source of information.
- FluxCD example repo: https://github.com/fluxcd/flux2-kustomize-helm-example, this example has helped a lot in structuring my repository.
