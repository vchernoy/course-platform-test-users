# course-platform-test-users

**Fake** student list for testing [course-platform](https://github.com/vchernoy/course-platform)'s multi-repo loading (`config/sources.yaml`, see its `docs/content-sources.md`).

- `config/students.yaml` enrolls test addresses in offerings that live in another repo, [course-platform-test-content](https://github.com/vchernoy/course-platform-test-content).
- This repo is public, so it must only ever contain `example.com` addresses. Real students go in a private repo.
