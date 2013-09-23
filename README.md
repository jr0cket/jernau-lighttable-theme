### Jernau: a Light Table theme

A dark theme with rainbow brackets:

<img src="https://raw.github.com/Misophistful/jernau-lighttable-theme/master/jernau-lightable-theme.png">

(Tested as working in Light Table version 0.5.3)

### Installation

Copy the css file to `/LightTable/core/css/themes/`, then update the `user.behavior` settings file with the following:

```clojure
;; The editor tag is applied to all editors
     :editor [:lt.objs.editor/no-wrap
              (:lt.objs.style/set-theme "jernau")]
```

(To open the `user.behavior` file use CTRL+SPACE to open the Command Panel, then search for "User behaviors".)
