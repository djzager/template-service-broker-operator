FROM ansibleplaybookbundle/apb-base:canary

# Add our role into the ansible roles dir
ADD playbooks /opt/apb/actions
ADD roles /opt/ansible/roles/

RUN chmod -R g=u /opt/{ansible,apb}

USER apb
