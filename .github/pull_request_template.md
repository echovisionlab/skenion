## Summary

- 

## Affected Repositories

- [ ] contracts
- [ ] examples
- [ ] runtime
- [ ] studio
- [ ] hub/docs

## Compatibility Checklist

- [ ] Contract schema or builtin ownership changes are documented.
- [ ] Canonical dataKind spelling remains `number.f32`, `event.bang`, `asset.video`, `video.frame`, `gpu.texture2d`, or `color.rgba` where applicable.
- [ ] Examples fixtures and project payloads still validate.
- [ ] Runtime validation/planning still accepts canonical examples.
- [ ] Studio registry or graph UX changes still consume contracts builtins.

## Validation

- [ ] Repository-local CI command:
- [ ] Cross-repo smoke, if compatibility-affecting: `bash scripts/smoke-compatibility.sh`
- [ ] Studio visual gate artifacts reviewed, if graph UX-affecting.

## Release Notes

- [ ] Conventional Commit title intentionally produces the desired Release Please behavior.
- [ ] No manual version bump was used as a substitute for a release PR.
