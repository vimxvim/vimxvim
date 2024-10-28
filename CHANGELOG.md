## 1.0.4

* Fix up compile issues on android and iOS.  Recreated the
  plugin wrapper from a flutter create method.

## 1.0.3

* **Breaking change**. Migrate from the deprecated original Android Support
  Library to AndroidX. This shouldn't result in any functional changes, but it
  requires any Android apps using this plugin to [also
  migrate](https://developer.android.com/jetpack/androidx/migrate) if they're
  using the original support library.
