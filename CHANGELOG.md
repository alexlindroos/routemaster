# 0.6.0

* Added `SafeArea` to default 404 page
* Fixed an issue navigating with relative paths and query strings
* Fixed an issue where the controller didn't update when tab length changed

# 0.5.0

* Fixed an issue where the root navigator would rebuild unnecessarily
* Added more useful assert errors
* Added default body for `RoutemasterObserver.didChangeRoute` so you're not forced to override it

# 0.4.0

* Added support for `RoutemasterObserver` in `RoutemasterDelegate`
* Added support for `NavigatorObserver` in `StackNavigator`
* Renamed `tabController` to `controller`

# 0.3.1

* Bug fix for reusing stacks in multiple navigators

# 0.3.0

* Added `StackNavigator` to simplify API
* Support for non-hash URLs on web - `Routemaster.setPathUrlStrategy()`
* Support for hero animations in nested navigators

# 0.2.0

* Re-work guards and redirects to make API simpler

# 0.1.0

* API hopefully becoming stable
* More flexible and customisable router config
* Support for "404" pages via `onUnknownRoute`
* Added Dashazon example, see `example/book_store/`

# 0.0.2

* Hugely improved and totally refactored API
* Null safety

# 0.0.1

* Initial first version
