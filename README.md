# Issue Report Javascript Action

This action creates a report based on the issues in a project which is passed in via parameter.

## Inputs

### `project`

**Required** The name of the project to create the report from. Default: NA.

## Outputs

### `outputFileName`

The name of the file created.

## Example usage

```yaml
uses: jsommer-enterprise-cloud-testing/Issue-Report@v0.1
with:
  project: 'ProjectX'
```