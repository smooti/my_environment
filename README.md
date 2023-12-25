## My VIM Configuration

```bash
# Run playbook on ansible controller and not in an execution environment
# Run `ansible-navigator` with prompts enabled
ansible-navigator run -m stdout --ep --ee false playbook.yml
```
