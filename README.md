Role to create multiple droplets from inventory group an group_vars

inventory/prod/hosts 
[civ_prod]
pwsciv301
pwsciv302
papciv301
papciv302

inventory/prod/group_vars/all.yaml
digital_ocean_env:
  DO_API_TOKEN: THE_DO_TOKEN_YOU_CREATED

inventory/prod/group_vars/civ_prod.yaml
ssh_key: b8:74:3d:7b:74:51:f4:54:bf:b7:d2:8e:2a:83:19:4c
dc: fra1
group: prod

