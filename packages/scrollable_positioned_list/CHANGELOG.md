# 0.1.5

  * Added minCacheExtent to ScrollablePositionedList
  * Fixes the issue when item count updated from zero to one and `index` in 
    `itemBuilder` becomes `-1`.  Fixes
    [issue #104](https://github.com/google/flutter.widgets/issues/104).

# 0.1.4

  *  itemBuilders should not be called with indices > itemCount - 1.  Fixes
     [issue #42](https://github.com/google/flutter.widgets/issues/42) and
     [issue #77](https://github.com/google/flutter.widgets/issues/77).

# 0.1.3

  * Don't build items when `itemCount` is 0. Fixes
    [issue #78](https://github.com/google/flutter.widgets/issues/78).

  * Fix typos in `README.md`.

# 0.1.2

  * Store scroll state in page storage to fix
    [issue #43](https://github.com/google/flutter.widgets/issues/43).

# 0.1.1

  * Fix padding for horizontal lists.

  * Add `ScrollablePositionedList.separated` constructor to complete
    [issue #34](https://github.com/google/flutter.widgets/issues/34).

  * Add `isAttached` method to `ItemScrollController`.

# 0.1.0

  * Properly bound `ScrollablePositionedList` to fix
    [issue #23](https://github.com/google/flutter.widgets/issues/23).

  * Allow `ScrollablePositionedList` alignment outside `[0..1]` to fix
    [issue #31](https://github.com/google/flutter.widgets/issues/31).

  * Moved `ScrollablePositionedList` example into `example` subdirectory.

# 0.0.1

* Added `ScrollablePositionedList`.
