# clang-cookbook

TODO: Enter the cookbook description here.

## Supported Platforms

TODO: List your supported platforms.

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['clang']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### clang::default

Include `clang` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[clang::default]"
  ]
}
```

## License and Authors

Author:: John Bellone (<jbellone@bloomberg.net>) (<jbellone@bloomberg.net>)
