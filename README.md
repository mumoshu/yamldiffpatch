# yamldiffpatch

Diff and patch YAML documents with RFC6902 JSON patches.

## Usage

Generate RFC6902-ish YAML document from diff:

```
yamldiffpatch diff --output yaml a.yaml b.yaml
```

Apply a patch:

```
yamldiffpatch patch a.yaml patch.yaml
```

## Acknowledgements

his project has been hugely inspired by the following awesome projects.

Thanks a lot for authors!

- https://github.com/krishicks/yaml-patch
- https://github.com/sahilm/yamldiff (takes textual diffs of two yaml files)
- https://github.com/homeport/dyff (takes prittified structured diff of two yaml files)
- https://github.com/evanphx/json-patch (applies RFC6902 json patches)
- https://github.com/mattbaird/jsonpatch (diff and produces RFC6902 json patches)
- https://github.com/benjamine/jsondiffpatch
