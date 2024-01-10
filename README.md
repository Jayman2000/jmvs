# Jason’s Modified Version of SemVer

I want to use [SemVer](https://semver.org) for my projects, but SemVer
has a significant problem: [In certain circumstances, you can’t release
a new version without breaking the SemVer spec.][1]

JMVS is the same thing as the upstream version of SemVer, but with [one
specific change that fixes that previously mentioned issue][2].
Hopefully, the upstream version of SemVer will be fixed one day so that
I can get rid of this fork.

The JMVS spec itself is in [`semver.md`](./semver.md). For my own
convenience, I didn’t bother renaming it. It still calls itself the
“Semantic Versioning Specification”.

[1]: https://github.com/semver/semver/pull/588#issuecomment-1716070281
[2]: https://github.com/semver/semver/pull/588#issuecomment-1725431372
