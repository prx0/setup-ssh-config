# ssh-config
Github action to configure SSH config file

```yml
    - name: Setup ssh config file 
      uses: prx0/ssh-config@v1
      with:
        host: [HOST_URL]
        hostname: [HOST_NAME]
        user: git
        private-key: [PRIVATE_KEY]
```
