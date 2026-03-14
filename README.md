# Ansible Library Utility Middleware.
Provides common testing patterns and middleware for complex operations.

> The ansible 2.19 and Molecule 25.1.0 changes effectively were breaking
> changes for pre-existing Collections. During updates additional changes were
> made during the 'unfreeze' as it provided a good opportunity to fix issues.
>
> Tests have moved to [r_pufky.data][a]. This collection is deprecation but
> will not be removed. Please feel free to fork the source if you need to
> continue to use this library pre-ansible 2.19.

See [Documentation][h] for development setup, requirements, and submission
practices. See Individual role documentation for usage.

## Related Collections
* [r_pufky.arr][a]: Manage media retrieval services.
* [r_pufky.deb][b]: Manage Debian OS foundational services.
* [r_pufky.game][c]: Manage linux dedicated gaming servers.
* [r_pufky.media][d]: Manage management and streaming services.
* [r_pufky.srv][e]: Manage services.
* [r_pufky.data][f]: Data annotations for structured data in ansible (ansible).
* [r_pufky.lib][g]: Ansible support library providing testing frameworks
  (ansible).

[Install from Galaxy][g].

## [Versions][i]

 Release | Debian | Ansible | Notes
---------|--------|---------|-------
 2.x.x   | 13     | 2.20    | Deprecated. Move to r_pufky.data.
 1.x.x   | 13     | 2.20    | Ansible 2.20, feature flags, and semantic versioning.
 0.x.x   | 12     | 2.11    | Pre-release migrations (old 12.x.x,13.x.x builds).

## License
[AGPL-3.0 License][j] | [(direct link)][k]

## Author Information
PGP: [466EEC2B67516C7117C85CE3A0BC35D16698BAB9][l] | [github gist][m]

[a]: https://galaxy.ansible.com/ui/repo/published/r_pufky/arr
[b]: https://galaxy.ansible.com/ui/repo/published/r_pufky/deb
[c]: https://galaxy.ansible.com/ui/repo/published/r_pufky/game
[d]: https://galaxy.ansible.com/ui/repo/published/r_pufky/media
[e]: https://galaxy.ansible.com/ui/repo/published/r_pufky/srv
[f]: https://galaxy.ansible.com/ui/repo/published/r_pufky/data
[g]: https://galaxy.ansible.com/ui/repo/published/r_pufky/lib
[h]: https://r-pufky.github.io/ansible_docs
[i]: https://semver.org/spec/v2.0.0

[j]: https://www.tldrlegal.com/license/gnu-affero-general-public-license-v3-agpl-3-0
[k]: https://github.com/r-pufky/ansible_tests/blob/main/LICENSE
[l]: https://keys.openpgp.org/vks/v1/by-fingerprint/466EEC2B67516C7117C85CE3A0BC35D16698BAB9
[m]: https://gist.github.com/r-pufky/a8df36977c55b5bb20829267c4c49d22
