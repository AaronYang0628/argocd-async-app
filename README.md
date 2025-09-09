
### Note

Thank you for your interest in this GitHub action, however, right now we are not taking contributions. 

We continue to focus our resources on strategic areas that help our customers be successful while making developers' lives easier. While GitHub Actions remains a key part of this vision, we are allocating resources towards other areas of Actions and are not taking contributions to this repository at this time. The GitHub public roadmap is the best place to follow along for any updates on features we’re working on and what stage they’re in.

We are taking the following steps to better direct requests related to GitHub Actions, including:

1. We will be directing questions and support requests to our [Community Discussions area](https://github.com/orgs/community/discussions/categories/actions)

2. High Priority bugs can be reported through Community Discussions or you can report these to our support team https://support.github.com/contact/bug-report.

3. Security Issues should be handled as per our [security.md](security.md)

We will still provide security updates for this project and fix major breaking changes during this time.

You are welcome to still raise bugs in this repo.

### What's new

Please refer to the [release page](https://github.com/actions/checkout/releases/latest) for the latest release notes.

### Usage
<!-- start usage -->
```yaml
- uses: aaronyang0628/argocd-sync-nginx-app@v1
  with:
    # 
    argocd-server: '192.168.58.2:30443'

    # [Optional] 
    # Default: 'admin'
    argocd-user: 'admin'

    # 
    argocd-token: 'AdQUx7gQLbzD74iF'

    # [Optional]
    # Default: ''
    insecure-option: '--insecure'
    # 
    # Default: ${{ github.repository }}
    application-yaml-path: 'sample/sample.nginx.app.yaml'
    
```
<!-- end usage -->