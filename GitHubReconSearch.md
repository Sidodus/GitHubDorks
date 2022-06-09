# GitHub Recon Search:

## Specific Org search:

- "Org_name" password
- "org_name" key
- "org_name" api
- "org_name" "filename:vim_settings.xml"
- "org_name" "Authorization: Bearer"
- "org_name" "Language: PHP"
- "Org_name" "company.com" "dev"
- "Org_name" "dev.company.com"
- "Org_name" "opensource.company.dev"
- "Org_name" "opensource.company.com"
- "Org_name" "company.com" API_key
- "Org_name" "company.com" password
- "Org_name" "api.company.com" authorization

## Sensitive Files search:

- path:sites databases password
- filename:manifest.xml
- filename:travis.yml
- filename:vim_settings.xml
- filename:database
- filename:secrets.yml password
- filename:.esmtprc password
- filename:passwd path:etc
- filename:dbeaver-data-sources.xml
- filename:config.php dbpasswd
- filename:.netrc password
- filename:\_netrc password
- filename:hub oauth_token
- filename:filezilla.xml Pass
- filename:recentservers.xml Pass
- filename:idea14.key
- filename:config irc_pass
- filename:connections.xml
- filename:express.conf path:.openshift
- filename:.pgpass
- filename:proftpdpasswd
- filename:ventrilo_srv.ini
- filename:settings.py SECRET_KEY
- filename:master.key path:config
- filename:deployment-config.json
- filename:.ftpconfig
- filename:.remote-sync.json
- filename:sftp.json path:.vscode
- filename:WebServers.xml
- filename:jupyter_notebook_config.json
- filename:logins.json
- filename:CCCam.cfg
- filename:.bash_history
- filename:.cshrc
- filename:.history
- filename:.sh_history
- filename:sshd_config
- filename:dhcpd.conf
- filename:prod.exs NOT prod.secret.exs
- filename:prod.secret.exs
- filename:configuration.php JConfig password
- filename:config.php pass
- filename:sftp-config.json
- filename:.npmrc \_auth
- filename:.dockercfg auth
- filename:shadow path:etc
- filename:id_rsa or filename:id_dsa
- filename:.tugboat NOT \_tugboat
- filename:server.cfg rcon password
- filename:credentials aws_access_key_id
- filename:.s3cfg
- filename:wp-config.php
- filename:.htpasswd
- filename:.env DB_USERNAME NOT homestead
- filename:.env MAIL_HOST=smtp.gmail.com
- filename:.git-credentials
- filename:.bashrc password
- filename:.bashrc mailchimp
- filename:.bash_profile aws
- msg nickserv identify filename:config
- rds.amazonaws.com password
- SF_USERNAME salesforce
- xoxp OR xoxb
- .mlab.com password

## Specific Language based search:

- language:python username
- language:php username
- language:sql username
- language:html password
- language:perl password
- language:shell username
- language:java api
- PT_TOKEN language:bash
- HOMEBREW_GITHUB_API_TOKEN language:shell
- shodan_api_key language:python
- shodan_api_key language:shell
- shodan_api_key language:json
- shodan_api_key language:ruby
- HEROKU_API_KEY language:shell
- HEROKU_API_KEY language:json

## API keys, Token & Hard-Coded Password search:

- SecretKey / Secrect_key / skey
- privatekey / private_key / pkey
- user_secret / userSecret
- admin_passwd / adminpasswd / adminPass etc
- "api keys"
- authorization_bearer:
- oauth
- auth
- authentication
- client_secret
- api_token:
- "api token"
- client_id
- password
- user_password
- user_pass
- passcode
- secret
- password hash
- OTP
- user auth
- JEKYLL_GITHUB_TOKEN

## Username search:

- user:name (user:admin)
- org:name (org:google type:users)
- in:login (<username> in:login)
- in:name (<username> in:name)
- fullname:firstname lastname (fullname:<name> <surname>)
- in:email (data in:email)

## GitHub Dorks for Finding Information using Dates:

- created:<2012–04–05
- created:>=2011–06–12
- created:2016–02–07 location:iceland
- created:2011–04–06..2013–01–14 <user> in:username

## Extension based search:

- extension:pem private
- extension:ppk private
- extension:sql mysql dump
- extension:sql mysql dump password
- extension:json api.forecast.io
- extension:json mongolab.com
- extension:yaml mongolab.com
- extension:json googleusercontent client_secret
- extension:avastlic "support.avast.com"
- [WFClient] Password= extension:ica
- jsforce extension:js conn.login

## Automated Tools:

1. [TruffleHog](https://github.com/dxa4481/truffleHog)
2. [WatchTower](https://radar.nightfall.ai/)

## NOTE :

If you find any API key or credentials or any other sensitive information under test directory then do not report it because that is an intended behaviour.

## Author:

[Mr.\_fr3qu3n533](https://twitter.com/mr_fr3qu3n533)
