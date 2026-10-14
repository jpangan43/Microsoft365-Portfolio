# SharePoint Site Architecture

## Proposed structure
- Corporate / Company Portal
- Finance
- HR
- Sales
- Operations
- Marketing

## Design principles
- Assign a primary and backup owner to each site.
- Use groups to manage access where practical.
- Keep confidential department content in appropriately restricted sites.
- Avoid breaking permission inheritance without a clear requirement and documentation.
- Review external sharing and sharing links.
- Separate communication-site needs from team collaboration-site needs.

## Procedure
1. Confirm the purpose and owner of each site.
2. Create a pilot site in SharePoint admin center.
3. Configure site privacy and external sharing in line with business requirements.
4. Assign owners and members using approved groups.
5. Upload only synthetic test files.
6. Test authorized and unauthorized access.
7. Document actual settings and evidence.

## Access matrix

| Site | Owners | Members | Visitors | External sharing |
|---|---|---|---|---|
| Corporate | Management / IT | Approved workforce | As approved | Restricted by policy |
| Finance | Finance owner | Finance group | None by default | Disabled unless approved |
| HR | HR owner | HR group | None by default | Disabled unless approved |
| Sales | Sales owner | Sales group | As approved | Business-approved only |
