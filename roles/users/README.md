добавляем пользователей, ключ должен лежать в files и называться name_id_rsa.pub

плейбук может вызываться через:

ansible-playbook -i host role.yml -- extra-vars "name=имя_пользователя" --extra-vars "group=docker,sudo"

или без доп переменной, имя пользователя добавлено в defaults
