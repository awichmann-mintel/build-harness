## increment the patch version number (i.e. 1.0.0 -> 1.0.1) and do a release.
bumpversion/release_patch: python/env
	$(WITH_PIPENV) bumpversion patch --verbose
	$(GIT) push --follow-tags
.PHONY: release_patch

## increment the minor version number (i.e. 1.0.0 -> 1.1.0) and do a release.
bumpversion/release_minor: python/env
	$(WITH_PIPENV) bumpversion minor --verbose
	$(GIT) push --follow-tags
.PHONY: release_minor

## increment the major version number (i.e. 1.0.0 -> 2.0.0) and do a release.
bumpversion/release_major: python/env
	$(WITH_PIPENV) bumpversion major --verbose
	$(GIT) push --follow-tags
.PHONY: release_major
