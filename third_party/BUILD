package(default_visibility = [
    "//:__subpackages__",
])

licenses(["notice"])  # Apache2

# TODO(dramaix): These externs files are being opensourced (see cl/154112993). We copied/pasted here
# for being able to test our bazel build. We will refer to the externs in closure-compiler github
# repo before to really opensource elemental2
exports_files([
    "mediakeys.js",
    "svg.js",
    "w3c_clipboardevent.js",
    ])

alias(
    name = "es3.js",
    actual = "@com_google_closure_compiler//:externs/es3.js",
)

alias(
    name = "es5.js",
    actual = "@com_google_closure_compiler//:externs/es5.js",
)

alias(
    name = "es6.js",
    actual = "@com_google_closure_compiler//:externs/es6.js",
)

alias(
    name = "es6_collections.js",
    actual = "@com_google_closure_compiler//:externs/es6_collections.js",
)

alias(
    name = "w3c_event.js",
    actual = "@com_google_closure_compiler//:externs/browser/w3c_event.js",
)

alias(
    name = "w3c_event3.js",
    actual = "@com_google_closure_compiler//:externs/browser/w3c_event3.js",
)

alias(
    name = "w3c_device_sensor_event.js",
    actual = "@com_google_closure_compiler//:externs/browser/w3c_device_sensor_event.js",
)

alias(
    name = "w3c_touch_event.js",
    actual = "@com_google_closure_compiler//:externs/browser/w3c_touch_event.js",
)

alias(
    name = "w3c_dom1.js",
    actual = "@com_google_closure_compiler//:externs/browser/w3c_dom1.js",
)

alias(
    name = "w3c_dom2.js",
    actual = "@com_google_closure_compiler//:externs/browser/w3c_dom2.js",
)

alias(
    name = "w3c_dom3.js",
    actual = "@com_google_closure_compiler//:externs/browser/w3c_dom3.js",
)

alias(
    name = "w3c_dom4.js",
    actual = "@com_google_closure_compiler//:externs/browser/w3c_dom4.js",
)

alias(
    name = "w3c_batterystatus.js",
    actual = "@com_google_closure_compiler//:externs/browser/w3c_batterystatus.js",
)

alias(
    name = "fileapi.js",
    actual = "@com_google_closure_compiler//:externs/browser/fileapi.js",
)

alias(
    name = "page_visibility.js",
    actual = "@com_google_closure_compiler//:externs/browser/page_visibility.js",
)

alias(
    name = "w3c_rtc.js",
    actual = "@com_google_closure_compiler//:externs/browser/w3c_rtc.js",
)

alias(
    name = "html5.js",
    actual = "@com_google_closure_compiler//:externs/browser/html5.js",
)

alias(
    name = "window.js",
    actual = "@com_google_closure_compiler//:externs/browser/window.js",
)

alias(
    name = "w3c_range.js",
    actual = "@com_google_closure_compiler//:externs/browser/w3c_range.js",
)

alias(
    name = "w3c_css.js",
    actual = "@com_google_closure_compiler//:externs/browser/w3c_css.js",
)

alias(
    name = "w3c_css3d.js",
    actual = "@com_google_closure_compiler//:externs/browser/w3c_css3d.js",
)

alias(
    name = "w3c_xml.js",
    actual = "@com_google_closure_compiler//:externs/browser/w3c_xml.js",
)

alias(
    name = "flash.js",
    actual = "@com_google_closure_compiler//:externs/browser/flash.js",
)

alias(
    name = "w3c_anim_timing.js",
    actual = "@com_google_closure_compiler//:externs/browser/w3c_anim_timing.js",
)

alias(
    name = "webkit_notifications.js",
    actual = "@com_google_closure_compiler//:externs/browser/webkit_notifications.js",
)

alias(
    name = "w3c_abort.js",
    actual = "@com_google_closure_compiler//:externs/browser/w3c_abort.js",
)

alias(
    name = "fetchapi.js",
    actual = "@com_google_closure_compiler//:externs/browser/fetchapi.js",
)

alias(
    name = "w3c_serviceworker.js",
    actual = "@com_google_closure_compiler//:externs/browser/w3c_serviceworker.js",
)
alias(
   name = "w3c_navigation_timing.js",
   actual = "@com_google_closure_compiler//:externs/browser/w3c_navigation_timing.js",
)

# TODO(dramaix): Not opensourced yet
#alias(
#   name = "w3c_clipboardevent.js",
#   actual = "@com_google_closure_compiler//:externs/browser/w3c_clipboardevent.js",
#)

alias(
   name = "w3c_eventsource.js",
   actual = "@com_google_closure_compiler//:externs/browser/w3c_eventsource.js",
)

alias(
   name = "w3c_elementtraversal.js",
   actual = "@com_google_closure_compiler//:externs/browser/w3c_elementtraversal.js",
)

alias(
   name = "w3c_selectors.js",
   actual = "@com_google_closure_compiler//:externs/browser/w3c_selectors.js",
)

alias(
   name = "w3c_geolocation.js",
   actual = "@com_google_closure_compiler//:externs/browser/w3c_geolocation.js",
)

alias(
   name = "w3c_indexeddb.js",
   actual = "@com_google_closure_compiler//:externs/browser/w3c_indexeddb.js",
)

# TODO(dramaix): Not opensourced yet
#alias(
#   name = "mediakeys.js",
#   actual = "@com_google_closure_compiler//:externs/browser/mediakeys.js",
#)

alias(
   name = "w3c_audio.js",
   actual = "@com_google_closure_compiler//:externs/browser/w3c_audio.js",
)

# TODO(dramaix): Not opensourced yet
#alias(
#   name = "svg.js",
#   actual = "@com_google_closure_compiler//:externs/browser/svg.js",
#)

alias(
   name = "webgl.js",
   actual = "@com_google_closure_compiler//:externs/browser/webgl.js",
)

alias(
   name = "webstorage.js",
   actual = "@com_google_closure_compiler//:externs/browser/webstorage.js",
)

alias(
    name = "streamsapi.js",
    actual = "@com_google_closure_compiler//:externs/browser/streamsapi.js",
)

java_library(
    name = "gwt-jsinterop-annotations",
    exports = ["@jsinterop_annotations//jar"],
)

java_library(
    name = "jsinterop-base",
    exports = ["@jsinterop_base//jar"],
)