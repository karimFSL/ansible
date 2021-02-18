# ansible
ansible repo


``` sudo ansible-playbook playbooks/<playbook>
```

ELK command:
curl -XDELETE localhost:9200/apache* pour supprimer les index commençant par apache par exemple

vérifier la syntaxe d'un fichier de configuration logstah
sudo /usr/share/logstash/bin/logstash --path.settings /etc/logstash -f /etc/logstash/conf.d/apache.conf -t