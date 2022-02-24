# checkout-private-actions
Checkout Private Actions

## Usage

```yml
- name: Checkout Private Actions
  uses: WRM-Software/checkout-private-actions@v1
  with:
    repository: org/your-private-action
    ref: v1.9
    token: ${{ secrets.GITHUB_TOKEN }}
    path: ./your-private-action
```