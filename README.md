# nunit reporter
Create an annotation of the build information and also list first n failed nunit tests

Example
```yaml
  - uses: xibz/nunit-reporter@v1.0.12
      if: always()
      with:
        reportTitle: v1
        path: Tests/*.xml
        access-token: ${{ secrets.GITHUB_TOKEN }}
```
