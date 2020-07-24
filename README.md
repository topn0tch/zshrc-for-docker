# zshrc-for-docker
Extended ~/.zshrc for Docker/Docker compose
```
vim ~/.zshrc
```

```
# Docker compose
alias dc-ps='docker-compose ps'
alias dc-start='docker-compose start'
alias dc-stop='docker-compose stop'
alias dc-restart='docker-compose restart'
alias dc-exec='docker-compose exec -it '
alias dc-up='docker-compose up -d'
alias dc-down='docker-compose down'
alias dc-logs='docker-compose logs -f '

# Docker
alias dstart='docker start'
alias dstop='docker stop'
alias dps='docker ps'
alias dlogs='docker logs -f '
```
