# todo conventions
- task is not done yet
@ task is in progress
+ task is done

__fix__ - small fix that doesn't introduce new functionality

__feat__ - change that introduces new functionality but doesn't break
           backward compatibility

__break__ - change that breaks backward compatibility

# setup project tasks (for the initial release)
Tasks in this section are all __fix__ because project is before initial release.
- replace-oncreate: add first tasks starting from this one

# fixes and improvements (post initial release)
This project will not be published via npm but it will still be deployed
i.e. released. So SEMVER won't be used but some custom versioning can be
used here, but in any case release notes would make sence for this project.

Tasks in this section will follow todo conventions.
