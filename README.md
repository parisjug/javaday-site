# Maven site operations

## Build and check locally

```bash
mvn clean site site:run
```

## Deploy sur github page

Update  `settings.xml`:

```xml
<server>
    <id>github</id>
    <password>OAUTH2TOKEN</password>
    <!-- it's password, not oauth2Token -->
</server>
```


Active profil `deploy` by running :

```bash
mvn clean site -Pdeploy
```

## Deploy with github action

create personnal acces token (in Settings > Developer settings > Personal access tokens) with  

- privileges
  - repo - Full control of private repositories
  - repo:status - Access commit status
  - repo_deployment - Access deployment status
  - public_repo - Access public repositories
- notifications - Access notifications
- user - Update all user data
  - user:email - Access user email addresses (read-only)
  - user:follow - Follow and unfollow users

in project > settings > secrets > actions create a repository secret named : GH_TOKEN.

then in order to publish a new version push a new tag for instance :

```bash
# create a tag you your current date
git tag 202203212101
# push your tag to the github web site
git push origin --tags
```
