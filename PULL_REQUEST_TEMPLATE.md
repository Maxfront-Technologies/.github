## Pull Request

### Summary

<!-- Briefly describe what this PR changes and why. -->

### Related Work

**Related API PR:**

<!-- Link the API PR if applicable. Use N/A if none. -->

**Related UI PR:**

<!-- Link the UI PR if applicable. Use N/A if none. -->

**Other Related PRs / Repositories:**

<!-- Include worker, mobile app, shared library, infrastructure, etc. -->

---

## Change Impact

### Database

* [ ] No database changes
* [ ] Database schema change included
* [ ] New migration included
* [ ] Existing migration modified
* [ ] Data migration / backfill required

### Configuration

* [ ] No configuration changes
* [ ] New configuration value added
* [ ] Existing configuration value modified
* [ ] Configuration value removed
* [ ] Secret / credential added or changed
* [ ] Environment-specific configuration required

**Configuration values:**

| Key            | Change | Required | Secret | Environments             |
| -------------- | ------ | -------- | ------ | ------------------------ |
| `Example__Key` | Added  | Yes      | No     | Dev, Staging, Production |

<!-- Never include actual secret values in the PR. -->

---

### API

* [ ] No API changes
* [ ] New endpoint added
* [ ] Existing endpoint modified
* [ ] Endpoint removed
* [ ] Request contract changed
* [ ] Response contract changed
* [ ] Authentication / authorization changed
* [ ] API change is backward compatible
* [ ] API documentation / OpenAPI updated

**API notes:**

<!-- Mention breaking changes or consumers that may be affected. -->

---

### UI

* [ ] No UI changes
* [ ] New page / component added
* [ ] Existing page / component modified
* [ ] API integration added or modified
* [ ] Permissions / role visibility changed
* [ ] Loading, empty and error states handled
* [ ] Responsive behaviour verified

**UI notes:**

<!-- Include screenshots where useful. -->

---

## Application Behaviour

* [ ] Existing functionality remains backward compatible
* [ ] Permissions / authorization have been considered
* [ ] Multi-tenant behaviour has been considered
* [ ] Validation has been added or updated where required
* [ ] Error handling has been considered
* [ ] Logging has been added or updated where appropriate
* [ ] Background jobs / scheduled jobs are unaffected or updated
* [ ] External integrations are unaffected or updated

---

## Testing

* [ ] Unit tests added / updated
* [ ] Integration tests added / updated
* [ ] Existing automated tests pass
* [ ] Manual testing completed
* [ ] Permission / role scenarios tested

## Deployment / Release Impact

* [ ] Can be deployed independently
* [ ] Requires related API/UI PR to be deployed
* [ ] Requires database migration
* [ ] Requires configuration changes before deployment
* [ ] Requires configuration changes after deployment
* [ ] Requires a specific deployment order
* [ ] Requires data migration / backfill
* [ ] Requires downtime
* [ ] Requires feature flag
* [ ] No special deployment steps

### Deployment Order

<!-- Example:
1. Add production configuration
2. Deploy API
3. Run database migration
4. Deploy UI
-->

### Rollback Considerations

<!-- Explain anything that makes rollback difficult, especially database or contract changes. -->

---

## Reviewer Checklist

* [ ] Change matches the linked requirement / issue
* [ ] Related API/UI PRs have been reviewed
* [ ] Database changes are safe
* [ ] Configuration changes are documented
* [ ] No secrets are committed
* [ ] Breaking changes are clearly identified
* [ ] Tests adequately cover the change
* [ ] Deployment requirements are clear
* [ ] Code follows project conventions
* [ ] PR is ready to merge
