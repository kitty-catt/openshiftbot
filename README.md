# openshift 4.7

    $ oc get is ruby -n openshift 
    NAME   IMAGE REPOSITORY                                                         TAGS                                             UPDATED
    ruby   default-route-openshift-image-registry.apps-crc.testing/openshift/ruby   2.5,2.5-ubi7,2.5-ubi8,2.6,2.6-ubi7 + 5 more...   2 weeks ago


# install ruby

    sudo snap install ruby --classic --channel=2.5/stable

# update the Gemfile

    $ bundle install
    Using bundler 2.2.3
    Using cinch 2.3.4
    Using rack 2.2.3
    Bundle complete! 2 Gemfile dependencies, 3 gems now installed.
    Use `bundle info [gemname]` to see where a bundled gem is installed.

