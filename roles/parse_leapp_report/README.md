# Parse Leapp Report

The `parse_leapp_report` role is used by the `analysis` or `upgrade` roles to check the Leapp pre-upgrade report for inhibitors.

## Role variables

| Name                    | Default value         | Description                                         |
|-------------------------|-----------------------|-----------------------------------------------------|
| result_filename         | "/var/log/leapp/leapp-report.txt" | Path of the Leapp pre-upgrade report file. |
| result_filename_prefix  | "/var/log/leapp/leapp-report      | The path used and the prefix name setting for the Leapp report |
| result_fact_cacheable   | "false" | Allow the parse leapp report to be included as a cacheable fact |

## Example playbook

This is a common role included by the `analysis` and `upgrade` roles. It does not need to be explicitly included in your playbook.

## Authors:
Bob Mader, Mike Savage, David Danielsson

## License

MIT
