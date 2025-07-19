# UnHided

MediaFlow Proxy for Hugging Face. Use this specific repo to replace the one indicated in [these instructions](https://github.com/mhdzumair/mediaflow-proxy?tab=readme-ov-file#option-3-hugging-face-space-deployment-guide-from-a-mediaflow-contributor).

## Env Vars
```
API_PASSWORD = Yourpassword
```
### Mamma Mia
If you want to install MammaMia addon as well put also that enviroment variable
```
TRANSPORT_ROUTES = {
    "all://*.ichigotv.net": {
        "verify_ssl": false
    },
    "all://ichigotv.net": {
        "verify_ssl": false
    }
}
```
