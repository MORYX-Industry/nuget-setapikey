# nuget-setapikey

Composite GitHub Action that runs `nuget setapikey` for a provided set of package sources

## Usage

```yml
  uses: moryx-industry/nuget-setapikey@main
  with:
    sources-file: sources.txt
    api-key: ${{ secrets.my_api_key }}
```

`sources-file` accepts simple text file, that lists all sources urls where the
`api-key` should be used for.


