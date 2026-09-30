# Development and Deployment Workflow

## Branches

- main: stable, production-ready code.
- develop: active development and integration.
- feature/*: isolated feature work.
- fix/*: bug fixes.

## Intended workflow

1. Make changes in a feature or fix branch.
2. Test locally or on staging.
3. Merge into develop.
4. Validate the staging site.
5. Merge the approved release into main.
6. Deploy main to production.

Production deployment is intentionally not configured yet. WordPress hosting, staging URL, SSH/SFTP credentials, and the preferred deployment method will be selected before automation is enabled.

## Safety rules

- Never commit WordPress database credentials or API keys.
- Never commit wp-config.php.
- Never deploy untested changes directly to production.
- Keep content in WordPress/SCF rather than hard-coding editable copy in templates.
