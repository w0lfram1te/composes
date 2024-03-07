# README

**deployment instructions**

- bring up wireguard compose (to create wireguard network)
- bring up syncthing
- all other systems as needed

```bash
# NOTE: does not work with current implementation. dependent on compose execution location.
docker compose -f {folder}/compose.yaml -f {folder}/compose.yaml up
```