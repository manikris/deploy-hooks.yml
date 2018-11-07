# deploy-hooks.yml
Shell Script to install java app
production:
    first_thing:
      - source: /.cloud66/files/java.sh
        destination: ~/java.sh
        target: rails
        sudo: true
        execute: true
        apply_during: build_only
        halt_on_error: true
        my new updated

