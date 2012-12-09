chef-server-bootstrap-berksfile
===============================

This Berksfile is used to create an OpsCode Chef server bootstrap tarball.

    berks install --path cookbooks
    tar cfz bootstrap-latest.tar.gz cookbooks
