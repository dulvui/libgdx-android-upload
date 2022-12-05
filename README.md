# libgdx-android-upload
Github Action to upload an Android libGDX application to Google Play Store
If you have problems with the action or need help simply open an issue.

## Table of contents
- [libgdx-android-upload](#libgdx-android-upload)
  - [Table of contents](#table-of-contents)
  - [Requirements](#requirements)
  - [Parameters](#parameters)
  - [Working examples](#working-examples)
  - [License](#license)

## Requirements
 - Google Play Store Developer Account
 - Google Service Account JSON file
 - libGDX Android Project

## Parameters
| key | required | default | description |
| ----|----------|---------|-------------|
| package-name | true |   | Android package name |
| release-track | false | internal  | Release track: production, beta, alpha, internalsharing, internal |
| service-account-json | false | service-account.json | Path tho your Google service-account.json file  |

## Working examples
You an find a working examples here:  
https://github.com/dulvui/sn4ke/blob/main/.github/workflows/upload-android.yml

## License
This software is licensed under the [MIT license](LICENSE).