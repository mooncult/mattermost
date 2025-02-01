# mooncult mattermost m(d)eployment

## Setup

With `uv` and `uvx`:

```sh
uvx --from ansible-core ansible-galaxy install -r requirements.yml
uvx --from ansible-core ansible-playbook _deploy_testchat.yml --check
```
