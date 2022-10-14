# appimage-testing

Appimage for testing
```
id: com.officialrajdeepsingh.blog
runtime: org.freedesktop.Platform
runtime-version: '21.08'
sdk: org.freedesktop.Sdk
command: static-blog-app
modules:
  - name: static-blog-app
    buildsystem: autotools
    no-autogen: true
    sources:
      - type: extra-data
        path: target/release/bundle/deb/static-blog-app_0.0.2_amd64.deb
        
```
