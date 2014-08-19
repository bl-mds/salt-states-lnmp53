The Salt States for Lnmp53

GitFS Backend 
fileserver_backend:
  - git
gitfs_remotes:
  - git@github.com:bl-mds/salt-states-lnmp53.git
ext_pillar:
   - git: master git@github.com:bl-mds/salt-states-lnmp53.git root=pillar
